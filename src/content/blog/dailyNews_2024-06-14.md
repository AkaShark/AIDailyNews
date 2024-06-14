---
title: "Daily News #2024-06-14"
date: "2024-06-14 08:33:01"
description: "🌟 WWDC24 第四天
🌟 Apple Intelligence: AI for the rest of us
🌟 跨平台规划
🌟 无法将 Sonoma 虚拟机升级到 macOS Sequoia Beta？试试这个！
🌟 WWDC24：visionOS 2 更新全解析
🌟Meta分享大规模训练语言模型的经验
🎉 Visual Studio 预览版中新增 Copilot Enterprise 功能
💨 Mistral.rs: Blazingly Fast LLM Inference
💧 Vapor：Swift 的 HTTP Web 框架"
tags: 
- '虚拟机'
- 'AI'
- '语言模型'
- 'WWDC24'
- 'LLM Inference'
- 'Swift'
- 'AR_VR'
- 'Visual Studio'

---

> - 🌟 WWDC24 第四天
> - 🌟 Apple Intelligence: AI for the rest of us
> - 🌟 跨平台规划
> - 🌟 无法将 Sonoma 虚拟机升级到 macOS Sequoia Beta？试试这个！
> - 🌟 WWDC24：visionOS 2 更新全解析
> - 🌟Meta分享大规模训练语言模型的经验
> - 🎉 Visual Studio 预览版中新增 Copilot Enterprise 功能
> - 💨 Mistral.rs: Blazingly Fast LLM Inference
> - 💧 Vapor：Swift 的 HTTP Web 框架

## Apple News

### [🌟 WWDC24 第四天](https://developer.apple.com/news/?id=sea5rkhq)

来源：Latest News - Apple Developer

发布时间：2024-06-13 22:00:42
![](https://devimages-cdn.apple.com/wwdc-services/articles/images/FAD4ECEF-212E-47C1-90FF-95BCB93819BD/2048.jpeg)
WWDC24 第四天的精彩内容，包括机器学习和人工智能、visionOS、游戏、Swift、开发者工具、SwiftUI 和 UI 框架、iOS 和 iPadOS、设计、watchOS 等主题。

### [🌟 Apple Intelligence: AI for the rest of us](https://www.apple.com/apple-intelligence/)

来源：Hacker News - Newest: "apple"

发布时间：2024-06-13 23:59:08

Apple Intelligence is a suite of AI-powered features coming to iPhones, iPads, and Macs this fall. It includes Writing Tools for enhanced text editing, Image Playground for creating custom images, and an improved Siri with expanded capabilities. Apple emphasizes the privacy-centric design of Apple Intelligence, which processes data on-device and uses Private Cloud Compute for more complex tasks while maintaining user privacy.

### [🌟 跨平台规划](https://developer.apple.com/news/?id=rfucqnzd)

来源：Latest News - Apple Developer

发布时间：2024-06-13 22:00:00
![](https://devimages-cdn.apple.com/wwdc-services/articles/images/CD368A80-DF56-4527-AC97-669DACDC0AE7/2048.jpeg)
了解 Apple 各平台的新功能，包括 visionOS 应用程序设计、将 iOS 或 iPadOS 游戏引入 visionOS 以及为系统体验设计应用程序意图。

### [🌟 无法将 Sonoma 虚拟机升级到 macOS Sequoia Beta？试试这个！](https://osxdaily.com/2024/06/12/cant-upgrade-a-sonoma-vm-to-macos-sequoia-beta-try-this/)

来源：OS X Daily

发布时间：2024-06-13 03:48:53

如果您已经在 UTM、Parallels、VMWare、VirtualBuddy 或其他软件中设置了 macOS Sonoma 虚拟机，您可能希望将 macOS Sonoma 虚拟机升级到 macOS Sequoia Beta 虚拟机。有人可能会认为，实现此目的的一种简单方法是在虚拟机中使用开发者 Apple ID 并安装...

## iOS Blog

### [🌟 WWDC24：visionOS 2 更新全解析](https://juejin.cn/post/7379296086539091980)

来源：掘金 iOS

发布时间：2024-06-13 10:17:57

WWDC24 中 visionOS 2 更新了众多功能，包括 ARKit、RealityKit、SwiftUI、Metal 与 WebXR 等主要模块。其中，ARKit 为 Vision Pro 提供了 6Dof 追踪、场景理解和识别等功能；RealityKit 为 Vision Pro 提供了原生 3D 渲染、动画、物理模拟、多人共享与协作等功能；SwiftUI 在 visionOS 中提供了很多系统级功能的支持，是 2D 与 3D 之间的桥梁；Metal 与 WebXR 为 Vision Pro 提供了第三方渲染的功能。此外，本次更新还弥补了手机 AR 与 Vision Pro 开发上的巨大差异，统一了开发 API 形式和功能。

## Tech News

### [🌟Meta分享大规模训练语言模型的经验](https://engineering.fb.com/2024/06/12/data-infrastructure/training-large-language-models-at-scale-meta/)

来源：Engineering at Meta

发布时间：2024-06-13 06:45:11

Meta分享了其在大规模训练语言模型方面的经验，重点介绍了其训练基础设施和技术。Meta使用分布式训练和优化算法来训练大规模语言模型，并开发了定制的硬件和软件解决方案来提高训练效率。Meta的方法使他们能够训练出最先进的语言模型，这些模型在各种自然语言处理任务上表现出色。

### [🎉 Visual Studio 预览版中新增 Copilot Enterprise 功能](https://github.blog/changelog/2024-06-13-new-copilot-enterprise-features-in-visual-studio-preview)

来源：Changelogs Archive - The GitHub Blog

发布时间：2024-06-13 22:43:12

Visual Studio 预览版中新增了 Copilot Enterprise 功能，包括代码补全、错误修复和代码生成，旨在提高开发人员的生产力和代码质量。

## Daily Code

### [💨 Mistral.rs: Blazingly Fast LLM Inference](https://github.com/EricLBuehler/mistral.rs)

来源：Trending repositories on GitHub today · GitHub

发布时间：2024-06-14 07:46:37

Mistral.rs is a fast and versatile LLM inference platform that supports quantization, device mapping, and easy integration with Rust, Python, and OpenAI API. It offers optimized performance for various models, including Mistral 7B, Llama, and Phi 3, and provides features like LoRA support, speculative decoding, and dynamic adapter swapping.

### [💧 Vapor：Swift 的 HTTP Web 框架](https://github.com/vapor/vapor)

来源：Trending Swift repositories on GitHub today · GitHub

发布时间：2024-06-14 05:47:47

Vapor 是一个用于 Swift 的 HTTP Web 框架，它为你的下一个网站、API 或云项目提供了一个非常富有表现力和易于使用的基础。Vapor 社区非常热情，欢迎加入 Discord 上的 Vapor 开发者社区。如果你发现了一个错误，请创建一个 issue。如果你发现了一个安全漏洞，请尽快联系 security@vapor.codes。
