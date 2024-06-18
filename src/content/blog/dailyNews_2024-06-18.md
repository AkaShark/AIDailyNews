---
title: "Daily News #2024-06-18"
date: "2024-06-18 08:34:05"
description: "🌟 iPadOS 18 新壁纸抢先看
苹果发现亚马逊云服务数据删除问题，促使亚马逊改进安全措施
🎉Xcode 16 来了！
🌟 WWDC 2024 观后感
🎉 SwiftUI 导航栏缩放过渡
Cocoapods-sled 让 iOS 组件二进制化变得简单
🎉 GitHub 支持推送保护委托绕过事件的 Webhook
🌟 WhisperKit：使用 CoreML 在 Apple 设备上进行高效本地推理的 Whisper 语音识别模型
🎨 ComfyUI：强大的稳定扩散 GUI 和后端"
tags: 
- '壁纸'
- '云安全'
- 'SwiftUI'
- 'GitHub'
- '二进制化'
- '图像生成'
- 'WWDC'
- '语音识别'
- 'Xcode 16'

---

> - 🌟 iPadOS 18 新壁纸抢先看
> - 苹果发现亚马逊云服务数据删除问题，促使亚马逊改进安全措施
> - 🎉Xcode 16 来了！
> - 🌟 WWDC 2024 观后感
> - 🎉 SwiftUI 导航栏缩放过渡
> - Cocoapods-sled 让 iOS 组件二进制化变得简单
> - 🎉 GitHub 支持推送保护委托绕过事件的 Webhook
> - 🌟 WhisperKit：使用 CoreML 在 Apple 设备上进行高效本地推理的 Whisper 语音识别模型
> - 🎨 ComfyUI：强大的稳定扩散 GUI 和后端

## Apple News

### [🌟 iPadOS 18 新壁纸抢先看](https://osxdaily.com/2024/06/16/get-the-ipados-18-default-wallpapers/)

来源：OS X Daily

发布时间：2024-06-17 00:12:54

iPadOS 18 中包含一系列新壁纸，色彩缤纷的有趣形状令人赏心悦目。虽然它们可能包含在 iPadOS 18 测试版中，但这并不意味着你必须勇敢地尝试测试版才能获得新的默认壁纸。

### [苹果发现亚马逊云服务数据删除问题，促使亚马逊改进安全措施](https://www.businessinsider.com/apple-alerted-amazon-potential-cloud-security-risk-aws-2024-6)

来源：Hacker News - Newest: "apple"

发布时间：2024-06-17 22:43:18

苹果发现亚马逊云服务（AWS）存在数据删除问题，AWS随后对数据删除流程进行了重大更改。AWS 承认存在问题，并表示已采取措施防止此类问题再次发生。此事件凸显了云安全的重要性，以及客户在控制其数据方面所面临的挑战。

## iOS Blog

### [🎉Xcode 16 来了！](https://juejin.cn/post/7381333086112546835)

来源：掘金 iOS

发布时间：2024-06-17 16:52:32

Xcode 16 带来了许多令人兴奋的新功能，包括改进的代码完成、Swift 6 更新、新的预览 API、显式模块、增强的调试功能、改进的测试和分析工具、新的资产管理功能、更新的模拟器以及本地化增强功能。

### [🌟 WWDC 2024 观后感](https://fatbobman.com/zh/weekly/issue-036/)

来源：肘子的 Swift 记事本 ｜ Fatbobman's Blog

发布时间：2024-06-17 22:00:00

WWDC 2024 展示了苹果在 AI、Swift、SwiftData 和 SwiftUI 方面的最新进展。苹果对 AI 的理解是避免华而不实的技术炫耀，重视隐私保护，让 AI 技术自然融入日常操作中。Swift 6 的推出标志着 Swift 迈向成熟的重要一步，苹果展示了对 Swift 的热情和更开放的态度。SwiftData 的最新版本带来了意外的震撼，底层的大幅调整使其具备成为一个跨平台开源框架的潜力。SwiftUI 的新特性在保持声明式框架特性的同时，有效提升了其表现力，并逐渐从仅基于 UIKit/AppKit 的框架转变为与苹果生态中其他 UI 框架更平等的合作伙伴。

### [🎉 SwiftUI 导航栏缩放过渡](https://augmentedcode.io/2024/06/17/zoom-navigation-transition-in-swiftui/)

来源：Blog – Augmented Code

发布时间：2024-06-17 23:00:00

WWDC'24 为 SwiftUI 带来了许多更新，其中之一是新的 NavigationTransition 协议和缩放过渡。这是一种为视图添加缩放过渡的内置方式。上手容易，但无法自定义。

### [Cocoapods-sled 让 iOS 组件二进制化变得简单](https://github.com/SwiftOldDriver/iOS-Weekly/releases/tag/%23293)

来源：Release notes from iOS-Weekly

发布时间：2024-06-17 10:10:49

二进制化是加快编译速度的常见手段，很多大厂在这个方向都做过不小的研究。但目前行业上还缺乏比较泛用的方案。cocoapods —— sled 这个插件就是为了解决这个问题，能针对 pod 进行二进制化并且能灵活的切换二进制和源码构建。有类似需求的小伙伴可以试试。

## Tech News

### [🎉 GitHub 支持推送保护委托绕过事件的 Webhook](https://github.blog/changelog/2024-06-17-webhook-support-for-push-protection-delegated-bypass-events)

来源：Changelogs Archive - The GitHub Blog

发布时间：2024-06-17 23:09:09

GitHub 现已支持为推送保护委托绕过事件配置 Webhook。这将允许用户在绕过推送保护时收到通知，从而提高安全性并简化审计。

## Daily Code

### [🌟 WhisperKit：使用 CoreML 在 Apple 设备上进行高效本地推理的 Whisper 语音识别模型](https://github.com/argmaxinc/WhisperKit)

来源：Trending Swift repositories on GitHub today · GitHub

发布时间：2024-06-18 07:01:19

WhisperKit 是一个 Swift 软件包，它将 OpenAI 流行的高性能语音识别模型 Whisper 与 Apple 的 CoreML 框架集成在一起，可在 Apple 设备上进行高效的本地推理。它支持从本地音频文件或麦克风流中进行转录，并允许选择特定的模型以满足不同的精度和速度要求。WhisperKit 还提供了生成和部署自定义微调 Whisper 模型的功能，并具有一个易于使用的 Swift CLI，用于快速测试和调试。

### [🎨 ComfyUI：强大的稳定扩散 GUI 和后端](https://github.com/comfyanonymous/ComfyUI)

来源：Trending repositories on GitHub today · GitHub

发布时间：2024-06-18 05:58:17

ComfyUI 是一个功能强大的稳定扩散 GUI 和后端，它允许用户使用基于图形/节点/流程图的界面设计和执行高级稳定扩散管道。它支持 SD1.x、SD2.x、SDXL、Stable Video Diffusion、Stable Cascade 和 SD3，并具有异步队列系统和许多优化功能。ComfyUI 还支持加载自定义模型、嵌入和文本反转，使其成为图像生成和探索的强大工具。
