---
title: "Daily News #2024-06-24"
date: "2024-06-24 08:34:56"
description: "怀旧！使用树莓派 Pico 微控制器模拟 Macintosh 128k
🎉 LLVM 编译器新增 Apple M4 支持，确认其 ISA 能力
🎉组件化通讯方案
📸 VisionCamera：React Native 的强大相机库"
tags: 
- '相机库'
- '处理器'
- '怀旧'
- 'React Native'
- '模拟'
- '组件化'

---

> - 怀旧！使用树莓派 Pico 微控制器模拟 Macintosh 128k
> - 🎉 LLVM 编译器新增 Apple M4 支持，确认其 ISA 能力
> - 🎉组件化通讯方案
> - 📸 VisionCamera：React Native 的强大相机库

## Apple News

### [怀旧！使用树莓派 Pico 微控制器模拟 Macintosh 128k](https://osxdaily.com/2024/06/23/fun-emulate-a-macintosh-128k-on-a-raspberry-pi-pico-microcontroller/)

来源：OS X Daily

发布时间：2024-06-23 23:20:33

使用树莓派 Pico 微控制器，你可以模拟一台完整的 Macintosh 128k，包括 VGA 视频和键盘/鼠标输入，这对于复古 Macintosh 和模拟爱好者来说是一个非常有趣且具有吸引力的项目。

### [🎉 LLVM 编译器新增 Apple M4 支持，确认其 ISA 能力](https://www.phoronix.com/forums/forum/hardware/processors-memory/1470926-apple-m4-support-added-to-the-llvm-compiler-confirming-its-isa-capabilities)

来源：Hacker News - Newest: "apple"

发布时间：2024-06-23 23:58:49

LLVM 编译器添加了对 Apple M4 处理器的支持，证实了其指令集架构 (ISA) 的能力。这表明 Apple 正在为其未来的处理器开发新的指令集，以提高性能和效率。

## iOS Blog

### [🎉组件化通讯方案](https://juejin.cn/post/7383205961194586139)

来源：掘金 iOS

发布时间：2024-06-23 13:01:16

本文主要介绍了组件化通讯的三种主流方案：URL路由、target-action和protocol匹配。URL路由适合经常开展运营活动的app，优点是动态性高，缺点是传参方式有限。target-action利用分类可以明确声明接口，进行编译检查，但需要在mediator和target中重新添加每一个接口，代码较为繁琐。protocol匹配利用接口调用，实现了参数传递时的类型安全，但只做了protocol和class的匹配，不支持更复杂的创建方式和依赖注入。

## Daily Code

### [📸 VisionCamera：React Native 的强大相机库](https://github.com/mrousavy/react-native-vision-camera)

来源：Trending Swift repositories on GitHub today · GitHub

发布时间：2024-06-24 07:09:10

VisionCamera 是一个功能强大、高性能的 React Native 相机库，它具有拍照、视频录制、二维码/条形码扫描、可自定义设备和多摄像头、可自定义分辨率和宽高比、可自定义 FPS、帧处理器、在相机上绘制形状、文本、滤镜或着色器、平滑缩放、快速暂停和恢复、HDR 和夜间模式、自定义 C++/GPU 加速视频管道等功能。
