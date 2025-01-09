---
title: "Daily News #2025-01-09"
date: "2025-01-09 08:39:56"
description: "Metal FlashAttention 2.0：推动 Apple 芯片上的设备推理和训练
🌟 SwiftUI 开发者大会
🥳iOS 18.3、macOS Sequoia 15.3、iPadOS 18.3 第二个测试版发布
💡 SwiftUI 搜索防抖：打造高效搜索体验"
tags: 
- 'iOS'
- '苹果芯片'
- 'SwiftUI'
- '人工智能'

---

> - Metal FlashAttention 2.0：推动 Apple 芯片上的设备推理和训练
> - 🌟 SwiftUI 开发者大会
> - 🥳iOS 18.3、macOS Sequoia 15.3、iPadOS 18.3 第二个测试版发布
> - 💡 SwiftUI 搜索防抖：打造高效搜索体验

## Apple News

### [Metal FlashAttention 2.0：推动 Apple 芯片上的设备推理和训练](https://engineering.drawthings.ai/metal-flashattention-2-0-pushing-forward-on-device-inference-training-on-apple-silicon-fe8aac1ab23c)

来源：Hacker News - Newest: "apple"

发布时间：2025-01-08 02:26:07

Metal FlashAttention 2.0 的主要版本升级提供了推理和训练的重大改进。将这些收益转化为实际数字，我们看到 M3/M4 设备上的 FLUX.1 模型推理提高了 20%，M3/M4 设备上的 SD3/AuraFlow 模型推理提高了 20%。SD3/AuraFlow 在较旧硬件上的类似改进，以及 FLUX.1 模型在较旧硬件上的约 2% 改进。与其他实现相比，Draw Things 中集成的 FLUX.1 在每次迭代中比 M2 Ultra 上的 mflux 实现快 25%，并且端到端时间更长；它比 ggml 实现（也称为 gguf 格式）快 94%。Draw Things 中集成的 SD Large 3.5 在每次迭代中比 DiffusionKit 实现快 163%（在 M2 Ultra 上）。

### [🌟 SwiftUI 开发者大会](https://developer.apple.com/news/?id=yijdyfo4)

来源：Latest News - Apple Developer

发布时间：2025-01-08 00:00:19
![](https://devimages-cdn.apple.com/wwdc-services/articles/images/A43E9EF4-A761-4BBD-A57B-900BA5A7EB75/2048.jpeg)
苹果开发者大会上，开发者们齐聚库比蒂诺，期待一场精彩的演讲。在他们面前，大屏幕上用脚本字体写着“Hello”一词。在新年第一期中：在库比蒂诺将 SwiftUI 带入你的应用程序，准备好迎接 Swift 学生挑战，结识 Oko 团队，等等。

### [🥳iOS 18.3、macOS Sequoia 15.3、iPadOS 18.3 第二个测试版发布](https://osxdaily.com/2025/01/07/beta-2-of-ios-18-3-macos-sequoia-15-3-ipados-18-3-available-for-beta-testers/)

来源：OS X Daily

发布时间：2025-01-08 07:00:06

苹果向测试人员发布了 iOS 18.3、iPadOS 18.3 和 macOS Sequoia 15.3 的第二个测试版。这些更新带来了错误修复和性能改进。

## iOS Blog

### [💡 SwiftUI 搜索防抖：打造高效搜索体验](https://danielsaidi.com/blog/2025/01/08/creating-a-debounced-search-context-for-performant-swiftui-searches)

来源：Daniel Saidi

发布时间：2025-01-08 14:00:00

本文介绍如何创建一个小型的可观察搜索上下文类，用于处理任何搜索操作的防抖，无需任何额外的工作。
