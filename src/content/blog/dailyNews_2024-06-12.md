---
title: "Daily News #2024-06-12"
date: "2024-06-12 01:04:51"
description: "苹果通过其平台上的新更新扩展其隐私领先地位
🌟 探索 Apple Intelligence，打造更强大的应用
📱 iOS 18 发布，带来深色模式图标、AI 功能、控制中心自定义等
🌟 WWDC24 第二天
🎉使用 SwiftUI 在 iOS 18 上构建一个可拉伸的头部视图
深入理解 Swift 中的 MainActor
🎉 SwiftUI 预览更轻松：@Previewable
🌟 WWDC 2024：AI 闪耀，新功能待体验
🌟 老司机 iOS 周报 #292
🎉 CodeQL 2.17.4：扩展查询自动修复，C++ PR 扫描更快
📸 VisionCamera：React Native 的强大相机库"
tags: 
- 'SwiftUI'
- '并发编程'
- 'MainActor'
- 'React Native'
- 'Apple Intelligence'
- 'iOS'
- 'CodeQL'
- 'AI'
- '相机'
- '技术'
- 'WWDC24'
- 'WWDC'
- 'Swift'

---

> - 苹果通过其平台上的新更新扩展其隐私领先地位
> - 🌟 探索 Apple Intelligence，打造更强大的应用
> - 📱 iOS 18 发布，带来深色模式图标、AI 功能、控制中心自定义等
> - 🌟 WWDC24 第二天
> - 🎉使用 SwiftUI 在 iOS 18 上构建一个可拉伸的头部视图
> - 深入理解 Swift 中的 MainActor
> - 🎉 SwiftUI 预览更轻松：@Previewable
> - 🌟 WWDC 2024：AI 闪耀，新功能待体验
> - 🌟 老司机 iOS 周报 #292
> - 🎉 CodeQL 2.17.4：扩展查询自动修复，C++ PR 扫描更快
> - 📸 VisionCamera：React Native 的强大相机库

## Apple News

### [苹果通过其平台上的新更新扩展其隐私领先地位](https://www.apple.com/newsroom/2024/06/apple-extends-its-privacy-leadership-with-new-updates-across-its-platforms/)

来源：Apple Newsroom

发布时间：2024-06-11 05:40:21

苹果宣布了其平台上的一系列新更新，以扩展其隐私领先地位，包括 Private Cloud Compute、改进的联系人权限、配件设置工具包以及更新的隐私和安全部分。

### [🌟 探索 Apple Intelligence，打造更强大的应用](https://developer.apple.com/news/?id=70yxbkf7)

来源：Latest News - Apple Developer

发布时间：2024-06-11 01:30:09

探索 Apple Intelligence，了解 Apple 平台的最新进展，包括全新的 Apple Intelligence，它可以帮助你创建更强大、更直观、更独特的体验。下载 Xcode 16、iOS 18、iPadOS 18、macOS 15、tvOS 18、visionOS 2 和 watchOS 11 的测试版，开始探索和使用最新功能。

### [📱 iOS 18 发布，带来深色模式图标、AI 功能、控制中心自定义等](https://osxdaily.com/2024/06/10/ios-18-announced-with-dark-mode-icons-ai-features-control-center-customizations-more/)

来源：OS X Daily

发布时间：2024-06-11 04:57:41

苹果宣布了 iOS 18，这是 iPhone 系统软件的下一个主要版本，它带来了一系列新功能、设计更新和更改。iOS 18 为主屏幕图标带来了全新的自定义选项，包括带有颜色着色的深色模式图标，可以在主屏幕上的任何位置放置图标和小组件，...

### [🌟 WWDC24 第二天](https://developer.apple.com/news/?id=9rlso3hi)

来源：Latest News - Apple Developer

发布时间：2024-06-11 23:28:40
![](https://devimages-cdn.apple.com/wwdc-services/articles/images/F566F6C5-BCCD-4CC7-99F5-D25E51E5F40E/2048.jpeg)
WWDC24 第二天，苹果开发者大会继续进行，涵盖机器学习、人工智能、visionOS、游戏、Swift、开发者工具、SwiftUI 和 UI 框架、iOS 和 iPadOS、设计、watchOS 等主题。

## iOS Blog

### [🎉使用 SwiftUI 在 iOS 18 上构建一个可拉伸的头部视图](https://www.donnywals.com/building-a-stretchy-header-view-with-swiftui-on-ios-18/)

来源：Donny Wals

发布时间：2024-06-11 21:13:59

在 iOS 18 中，SwiftUI 的 ScrollView 变得更加强大。它为 ScrollView 提供了多项新功能，赋予开发者更多控制权。我最喜欢的滚动视图交互之一是，当我在列表上拖动时，头部图像会随之动画。在 UIKit 中，我们会实现一个 UIScrollViewDelegate 并读取滚动时的内容偏移量。在 SwiftUI 中，我们可以使用 GeometryReader 实现可拉伸的头部效果，但这从来都不是一个好的解决方案。在 iOS 18 中，我们可以使用 onScrollGeometryChange 视图修饰符，几乎不需要任何解决方法即可实现可拉伸的头部。

### [深入理解 Swift 中的 MainActor](https://juejin.cn/post/7378363694940422154)

来源：掘金 iOS

发布时间：2024-06-11 10:23:19

在 Swift 5.5 中，引入了并发模型以简化多线程编程，并确保代码的安全和高效执行。`MainActor` 是这个新模型中的一个重要组件，它确保标记的代码在主线程上执行。本文将深入探讨 `MainActor` 的底层实现原理，了解其工作机制，并通过代码示例加以说明。

### [🎉 SwiftUI 预览更轻松：@Previewable](https://www.avanderlee.com/swiftui/previewable-macro-usage-in-previews/)

来源：SwiftLee

发布时间：2024-06-11 15:39:09

Xcode 16 引入了 SwiftUI 预览的 @Previewable 宏，允许你在预览中内联使用动态属性。你将能够对 SwiftUI 视图进行更丰富、更动态的预览，而无需在子视图中包装任何状态。

### [🌟 WWDC 2024：AI 闪耀，新功能待体验](https://fatbobman.com/zh/weekly/issue-035/)

来源：肘子的 Swift 记事本 ｜ Fatbobman's Blog

发布时间：2024-06-11 22:00:00

WWDC 2024 发布了众多新功能，AI 成为亮点，但部分功能需要等待一段时间才能体验。Swift、VisionOS 等也获得重大升级，但 SwiftData 出现不稳定性，建议开发者谨慎使用。

### [🌟 老司机 iOS 周报 #292](https://github.com/SwiftOldDriver/iOS-Weekly/releases/tag/%23292)

来源：Release notes from iOS-Weekly

发布时间：2024-06-11 10:02:42

本期周报包含了 WWDC24 内参目录、SwiftUI 相关技巧和最佳实践、Accelerate 框架介绍、声明式 API 设计、惰性容器使用技巧、字符串格式化优化工具 ZippyFormat 介绍等内容，内容丰富且实用。

## Tech News

### [🎉 CodeQL 2.17.4：扩展查询自动修复，C++ PR 扫描更快](https://github.blog/changelog/2024-06-11-codeql-2-17-4-autofixes-for-extended-queries-faster-c-pr-scans)

来源：Changelogs Archive - The GitHub Blog

发布时间：2024-06-11 22:46:14

CodeQL 2.17.4 现已推出，带来了一些令人兴奋的新功能和改进。最值得注意的是，我们添加了对扩展查询的支持，这将使编写更复杂、更强大的查询变得更加容易。我们还改进了 C++ PR 扫描的速度，使其比以往任何时候都更快。此外，我们还修复了一些错误并进行了其他一些改进。

## Daily Code

### [📸 VisionCamera：React Native 的强大相机库](https://github.com/mrousavy/react-native-vision-camera)

来源：Trending Swift repositories on GitHub today · GitHub

发布时间：2024-06-12 00:59:12

VisionCamera 是一个功能强大、高性能的 React Native 相机库，提供照片和视频捕捉、QR/条形码扫描、可定制设备和多摄像头、可定制分辨率和宽高比、可定制 FPS、帧处理器、在相机上绘制形状、文本、滤镜或着色器、平滑缩放、快速暂停和恢复、HDR 和夜间模式、自定义 C++/GPU 加速视频管道等功能。
