---
title: "Daily News #2024-12-25"
date: "2024-12-25 08:39:25"
description: "Abnormally slow loop (25x) under OCaml 5 / macOS / arm64
🤔 SwiftUI 6 中为何某些视图修饰器无法使用 @State 属性？"
tags: 
- 'Technical'
- 'SwiftUI'

---

> - Abnormally slow loop (25x) under OCaml 5 / macOS / arm64
> - 🤔 SwiftUI 6 中为何某些视图修饰器无法使用 @State 属性？

## Apple News

### [Abnormally slow loop (25x) under OCaml 5 / macOS / arm64](https://github.com/ocaml/ocaml/issues/13262)

来源：Hacker News - Newest: "apple"

发布时间：2024-12-24 03:24:28

A loop that writes values into an integer array is about 20x slower with OCaml 5 than with OCaml 4. Using Array.set versus Array.unsafe_set does not make much difference. Array.set
Array.unsafe_set
If the loop is manually unrolled (5 times) then this surprising slowness disappears.
To reproduce the problem:
git clone git@github.com:fpottier/array_set_loop.git
cd array_set_loop
make test
On OCaml 4.14.2, I get the following (normal) results:
main $ make test
Benchmark 1: _build/default/main.exe
  Time (mean ± σ):      10.6 ms ±   0.1 ms    [User: 9.8 ms, System: 0.6 ms]
  Range (min … max):    10.2 ms …  10.9 ms    281 runs

Benchmark 2: _build/default/main.exe --unsafe
  Time (mean ± σ):       8.4 ms ±   0.1 ms    [User: 7.6 ms, System: 0.6 ms]
  Range (min … max):     8.1 ms …   9.1 ms    357 runs

Benchmark 3: _build/default/main.exe --unrolled
  Time (mean ± σ):       9.1 ms ±   0.1 ms    [User: 8.3 ms, System: 0.6 ms]
  Range (min … max):     8.9 ms …   9.3 ms    328 runs

Benchmark 4: _build/default/main.exe --unsafe --unrolled
  Time (mean ± σ):       7.7 ms ±   0.1 ms    [User: 6.9 ms, System: 0.6 ms]
  Range (min … max):     7.5 ms …   8.2 ms    381 runs

Summary
  _build/default/main.exe --unsafe --unrolled ran
    1.09 ± 0.02 times faster than _build/default/main.exe --unsafe
    1.18 ± 0.02 times faster than _build/default/main.exe --unrolled
    1.38 ± 0.02 times faster than _build/default/main.exe

On OCaml 5.x, I get the following abnormal results:
main $ make test
Benchmark 1: _build/default/main.exe
  Time (mean ± σ):     187.3 ms ±  10.9 ms    [User: 184.2 ms, System: 2.8 ms]
  Range (min … max):   155.3 ms … 206.4 ms    30 runs

Benchmark 2: _build/default/main.exe --unsafe
  Time (mean ± σ):     191.2 ms ±  11.8 ms    [User: 188.1 ms, System: 2.8 ms]
  Range (min … max):   156.4 ms … 210.7 ms    30 runs

Benchmark 3: _build/default/main.exe --unrolled
  Time (mean ± σ):       7.6 ms ±   0.1 ms    [User: 6.8 ms, System: 0.6 ms]
  Range (min … max):     7.4 ms …   8.0 ms    391 runs

Benchmark 4: _build/default/main.exe --unsafe --unrolled
  Time (mean ± σ):       7.6 ms ±   0.1 ms    [User: 6.7 ms, System: 0.6 ms]
  Range (min … max):     7.4 ms …   7.9 ms    388 runs

Summary
  _build/default/main.exe --unsafe --unrolled ran
    1.01 ± 0.02 times faster than _build/default/main.exe --unrolled
   24.70 ± 1.47 times faster than _build/default/main.exe
   25.22 ± 1.58 times faster than _build/default/main.exe --unsafe

I have tried OCaml 5.0, 5.1, and 5.2, and get similar results.
In the unrolled loop, the safe point (_caml_call_gc) is executed only once every 5 iterations. So, my (uninformed) guess is that somehow, if _caml_call_gc is called too often, it becomes very slow (?).
_caml_call_gc
_caml_call_gc

## iOS Blog

### [🤔 SwiftUI 6 中为何某些视图修饰器无法使用 @State 属性？](https://fatbobman.com/zh/posts/why-certain-view-modifiers-in-swift-6-cannot-usethe-state-property/)

来源：肘子的 Swift 记事本 ｜ Fatbobman's Blog

发布时间：2024-12-24 08:12:00

在 Swift 6 模式下，由于并发检查要求更严格，某些视图修饰器（如 alignmentGuide）无法直接使用 @State 属性。这是因为 @State 属性的 getter 方法被标记为 @MainActor，而 @Sendable 闭包中不允许调用 @MainActor 方法。解决方法是使用 wrappedValue 或在闭包外预先获取 State 的值。
