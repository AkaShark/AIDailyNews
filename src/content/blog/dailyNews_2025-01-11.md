---
title: "Daily News #2025-01-11"
date: "2025-01-11 08:40:33"
description: "Combining Machine Learning and Homomorphic Encryption in the Apple Ecosystem
🎉 Apple Pay 服务器连接安全算法更新
🎉Apple Arcade 2025 年首发 10 款新游戏，包括 PGA TOUR Pro Golf
🗣️ macOS上使用「输入给Siri」功能更简单了
🌟 解决 Swift 中“主线程隔离属性无法从可发送闭包中引用”的问题
🧐 超参数在 AI 模型微调中的作用
🎉 GitHub Secret 扫描扩展了默认模式支持"
tags: 
- 'AI 模型微调'
- '游戏'
- '安全'
- 'Swift'
- 'Technology'
- 'Siri'
- 'Apple Pay'

---

> - Combining Machine Learning and Homomorphic Encryption in the Apple Ecosystem
> - 🎉 Apple Pay 服务器连接安全算法更新
> - 🎉Apple Arcade 2025 年首发 10 款新游戏，包括 PGA TOUR Pro Golf
> - 🗣️ macOS上使用「输入给Siri」功能更简单了
> - 🌟 解决 Swift 中“主线程隔离属性无法从可发送闭包中引用”的问题
> - 🧐 超参数在 AI 模型微调中的作用
> - 🎉 GitHub Secret 扫描扩展了默认模式支持

## Apple News

### [Combining Machine Learning and Homomorphic Encryption in the Apple Ecosystem](https://machinelearning.apple.com/research/homomorphic-encryption)

来源：Hacker News - Newest: "apple"

发布时间：2025-01-10 04:44:38

Apple's implementation of homomorphic encryption (HE) enables private server lookups and enhances on-device ML experiences. HE allows clients to encrypt queries before sending them to servers, ensuring that the server does not have access to the original request or decryption key. Apple combines HE with private information retrieval (PIR) and private nearest neighbor search (PNNS) to protect user privacy in various applications, such as Enhanced Visual Search for Photos. The open-sourced swift-homomorphic-encryption library empowers developers to adopt HE for their own applications.

### [🎉 Apple Pay 服务器连接安全算法更新](https://developer.apple.com/news/?id=2x8awlvm)

来源：Latest News - Apple Developer

发布时间：2025-01-10 00:00:14

苹果将于下个月更新 Apple Pay 网络版服务器连接的安全算法。为确保服务不中断，您需要在 2025 年 2 月 4 日之前确保您的生产服务器支持指定的六种密码中的至少一种。此算法更改将影响您在 Apple Pay 集成中建立的任何安全连接，包括以下接触点：请求 Apple Pay 支付会话（仅限 Apple Pay 网络版）、续订您的域名验证（仅限 Apple Pay 网络版）、接收和处理经常性、递延和自动充值交易的商家令牌通知（Apple Pay 网络版和应用内）、创建和更新钱包订单（Apple Pay 网络版和应用内）、通过 Apple Pay 网络商家注册 API 管理商家入驻（仅限支付服务提供商 (PSP) 和电子商务平台）。

### [🎉Apple Arcade 2025 年首发 10 款新游戏，包括 PGA TOUR Pro Golf](https://www.apple.com/newsroom/2025/01/apple-arcade-launches-into-2025-with-10-new-games-including-pga-tour-pro-golf/)

来源：Apple Newsroom

发布时间：2025-01-10 22:59:30

Apple Arcade 宣布推出 10 款新游戏，包括备受期待的 PGA TOUR Pro Golf，以及来自 App Store 的获奖游戏，例如 FINAL FANTASY+ 和 Trials of Mana+。此外，现有热门游戏还将迎来重大更新。

### [🗣️ macOS上使用「输入给Siri」功能更简单了](https://osxdaily.com/2025/01/09/use-type-to-siri-mac-easy-macos/)

来源：OS X Daily

发布时间：2025-01-10 05:35:36

在最新的macOS版本中，Siri有了显著的改进，主要是因为它现在与ChatGPT相关联。Siri的另一个变化是现在更容易访问「输入给Siri」功能，不再需要单独启用辅助功能设置。

## iOS Blog

### [🌟 解决 Swift 中“主线程隔离属性无法从可发送闭包中引用”的问题](https://www.donnywals.com/solving-main-actor-isolated-property-can-not-be-referenced-from-a-sendable-closure-in-swift/)

来源：Donny Wals

发布时间：2025-01-10 17:17:29

当开启严格并发检查或使用 Swift 6 语言模式时，可能会遇到“主线程隔离属性无法从可发送闭包中引用”的错误。本文提供了三种解决方法：修改接收闭包的函数、在闭包的捕获列表中捕获属性值、使用 MainActor.run 或非结构化任务从主线程修改值。

## Tech News

### [🧐 超参数在 AI 模型微调中的作用](https://www.artificialintelligence-news.com/news/the-role-of-hyperparameters-in-fine-tuning-ai-models/?utm_source=rss&utm_medium=rss&utm_campaign=the-role-of-hyperparameters-in-fine-tuning-ai-models)

来源：AI News

发布时间：2025-01-10 22:19:52

微调就像教一个预训练的 AI 模型一个新技巧。通过调整超参数，可以根据特定需求对 AI 模型进行微调。超参数在 AI 模型微调中起着至关重要的作用，可以优化模型的性能和准确性。

### [🎉 GitHub Secret 扫描扩展了默认模式支持](https://github.blog/changelog/2025-01-09-secret-scanning-expands-default-pattern-support)

来源：GitHub Changelog

发布时间：2025-01-10 06:05:42

GitHub Secret 扫描现在支持更多默认模式，这将使开发人员更容易发现和修复存储库中的秘密。新的默认模式包括对常见编程语言（如 Python、Java 和 JavaScript）中使用的常见秘密模式的支持。
