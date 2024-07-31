---
title: "Daily News #2024-07-31"
date: "2024-07-31 08:29:20"
description: "🌟 苹果使用谷歌 Tensor 芯片开发 Apple Intelligence
🌟 iOS 18.1、macOS Sequoia 15.1 和 iPadOS 18.1 首个测试版发布，搭载 Apple Intelligence AI 功能
🎉 Swift 同态加密库发布！
visionOS：苹果的增强现实和虚拟现实操作系统
🌟 非可发送类型：并发编程中的重要角色
🤖️ 摩根大通推出内部AI聊天机器人进行研究分析
✨ 手动运行作为 workflow_dispatch 设置的工作流
RxSwift: Reactive Programming in Swift
MinerU：基于 PDF-Extract-Kit 的端到端 PDF 解析工具，支持将 PDF 转换为 Markdown"
tags: 
- 'GitHub'
- '并发编程'
- 'AR_VR'
- 'PDF'
- 'AI'
- 'Swift'
- 'Reactive Programming'
- '人工智能'
- 'iOS'
- '数据提取'

---

> - 🌟 苹果使用谷歌 Tensor 芯片开发 Apple Intelligence
> - 🌟 iOS 18.1、macOS Sequoia 15.1 和 iPadOS 18.1 首个测试版发布，搭载 Apple Intelligence AI 功能
> - 🎉 Swift 同态加密库发布！
> - visionOS：苹果的增强现实和虚拟现实操作系统
> - 🌟 非可发送类型：并发编程中的重要角色
> - 🤖️ 摩根大通推出内部AI聊天机器人进行研究分析
> - ✨ 手动运行作为 workflow_dispatch 设置的工作流
> - RxSwift: Reactive Programming in Swift
> - MinerU：基于 PDF-Extract-Kit 的端到端 PDF 解析工具，支持将 PDF 转换为 Markdown

## Apple News

### [🌟 苹果使用谷歌 Tensor 芯片开发 Apple Intelligence](https://www.macrumors.com/2024/07/30/google-chips-used-to-develop-apple-intelligence/)

来源：Hacker News - Newest: "apple"

发布时间：2024-07-30 21:05:44

苹果使用谷歌开发的张量处理单元 (TPU) 构建了 Apple Intelligence 的两个关键组件，而不是英伟达广泛使用的图形处理单元 (GPU)。这一决定值得注意，因为英伟达在人工智能处理器市场占据主导地位，而苹果很少透露其用于开发目的的硬件选择。英伟达的 GPU 因其性能和效率而备受人工智能应用的青睐。与将芯片和系统作为独立产品销售的英伟达不同，谷歌通过云服务提供对 TPU 的访问。使用谷歌 TPU 的客户必须在谷歌的生态系统中开发他们的软件，该生态系统提供集成工具和服务，以简化人工智能模型的开发和部署。

### [🌟 iOS 18.1、macOS Sequoia 15.1 和 iPadOS 18.1 首个测试版发布，搭载 Apple Intelligence AI 功能](https://osxdaily.com/2024/07/29/beta-1-of-ios-18-1-macos-sequoia-15-1-ipados-18-1-released-with-apple-intelligence/)

来源：OS X Daily

发布时间：2024-07-30 06:06:02

苹果发布了 iOS 18.1、macOS Sequoia 15.1 和 iPadOS 18.1 的第一个测试版，均搭载了 Apple Intelligence AI 功能。这些测试版与 iOS 18、iPadOS 18 和 macOS Sequoia 15 的并发测试版是分开的，目前仍为测试版 4。

## iOS Blog

### [🎉 Swift 同态加密库发布！](https://swift.org/blog/announcing-swift-homomorphic-encryption/)

来源：Swift.org

发布时间：2024-07-30 18:00:00

苹果公司发布了 Swift 同态加密库，该库允许在不透露底层未加密数据的情况下对加密数据进行计算。它为客户端提供了一种将加密数据发送到服务器的方法，服务器对加密数据进行操作并返回客户端可以解密的结果。在执行请求期间，服务器本身永远不会解密原始数据，甚至无法访问解密密钥。这种方法为云服务在保护用户数据隐私和安全的同时进行操作提供了新的机会，这显然对许多场景极具吸引力。

### [visionOS：苹果的增强现实和虚拟现实操作系统](https://juejin.cn/post/7397030700467290153)

来源：掘金 iOS

发布时间：2024-07-30 10:57:51

本文介绍了 visionOS 的关键特性、开发工具和创建第一个 visionOS 程序的步骤，重点介绍了空间计算、Immersive Space、SwiftUI 和 ARKit 等技术，为开发者提供了全面了解 visionOS 开发的指南。

### [🌟 非可发送类型：并发编程中的重要角色](https://massicotte.org/non-sendable)

来源：massicotte.org

发布时间：2024-07-30 12:00:00

可发送类型在 Swift 并发编程中备受关注，但非可发送类型同样重要。它们通常被视为并发问题，但有时却是完美的解决方案。

## Tech News

### [🤖️ 摩根大通推出内部AI聊天机器人进行研究分析](https://www.artificialintelligence-news.com/news/jpmorgan-introduces-in-house-ai-chatbot-for-research-analysis/)

来源：AI News

发布时间：2024-07-30 18:44:49

摩根大通推出了一款尖端的生成式AI产品，突显了AI在金融业中日益增长的影响力。据《金融时报》获得的一份内部备忘录显示，这款名为LLM Suite的新工具被誉为颠覆者，能够执行传统上分配给研究分析师的任务...

### [✨ 手动运行作为 workflow_dispatch 设置的工作流](https://github.blog/changelog/2024-07-30-run-workflows-set-as-workflow_dispatch-manually)

来源：Changelogs Archive - The GitHub Blog

发布时间：2024-07-30 23:57:40

现在，您可以手动运行作为 `workflow_dispatch` 设置的工作流。这使您可以根据需要触发工作流，而无需等待触发事件。

## Daily Code

### [RxSwift: Reactive Programming in Swift](https://github.com/ReactiveX/RxSwift)

来源：Trending Swift repositories on GitHub today · GitHub

发布时间：2024-07-31 07:26:57

RxSwift is a library for reactive programming in Swift. It provides a way to represent and compose asynchronous operations and streams of data. RxSwift can be used to simplify the development of complex asynchronous applications.

### [MinerU：基于 PDF-Extract-Kit 的端到端 PDF 解析工具，支持将 PDF 转换为 Markdown](https://github.com/opendatalab/MinerU)

来源：Trending repositories on GitHub today · GitHub

发布时间：2024-07-31 06:51:35

MinerU 是一款一站式、开源、高质量的数据提取工具，包括以下主要功能：

Magic-PDF PDF 文档提取
Magic-Doc 网页和电子书提取

Magic-PDF 是一款旨在将 PDF 文档转换为 Markdown 格式的工具，能够处理存储在本地或支持 S3 协议的对象存储上的文件。
