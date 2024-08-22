---
title: "Daily News #2024-08-22"
date: "2024-08-22 08:36:06"
description: "🎉 4-H 携手 Apple，为新一代学习者带来科技力量！
🥳 iOS 18 beta 7 已发布，或为最终测试版
🎉 SwiftNIO Oblivious HTTP：保护隐私的 HTTP 协议
🤔 解决 Swift 6 中的“Task-isolated value of type ‘() async -> Void’ passed as a strongly transferred parameter”错误
🤯 在 Swift 中同步调用 Swift 并发异步代码
🎉 iOS 开发者必备：App Store 优化指南
🤖️人工智能基础设施的未来
💡企业治理中人工智能的使用必须在董事会层面得到改善
🎉 GitHub 安全配置新增非提供商模式的密钥扫描
The Composable Architecture 🧩
⚡️ 高性能 JavaScript 实用程序库：es-toolkit"
tags: 
- 'Swift'
- 'Swift 6'
- 'iOS'
- 'JavaScript'
- '安全'
- 'App Store 优化'
- '人工智能'
- 'Architecture'
- '教育'
- '网络安全'

---

> - 🎉 4-H 携手 Apple，为新一代学习者带来科技力量！
> - 🥳 iOS 18 beta 7 已发布，或为最终测试版
> - 🎉 SwiftNIO Oblivious HTTP：保护隐私的 HTTP 协议
> - 🤔 解决 Swift 6 中的“Task-isolated value of type ‘() async -> Void’ passed as a strongly transferred parameter”错误
> - 🤯 在 Swift 中同步调用 Swift 并发异步代码
> - 🎉 iOS 开发者必备：App Store 优化指南
> - 🤖️人工智能基础设施的未来
> - 💡企业治理中人工智能的使用必须在董事会层面得到改善
> - 🎉 GitHub 安全配置新增非提供商模式的密钥扫描
> - The Composable Architecture 🧩
> - ⚡️ 高性能 JavaScript 实用程序库：es-toolkit

## Apple News

### [🎉 4-H 携手 Apple，为新一代学习者带来科技力量！](https://www.apple.com/newsroom/2024/08/apple-and-4-h-are-bringing-technology-to-a-new-generation-of-learners/)

来源：Apple Newsroom

发布时间：2024-08-21 20:59:09

4-H 组织与 Apple 合作，将科技融入传统农业和手工技能的学习中，为美国超过 600 万的年轻人提供编码、创意和职业机会，帮助他们为未来做好准备。

### [🥳 iOS 18 beta 7 已发布，或为最终测试版](https://osxdaily.com/2024/08/20/ios-18-beta-7-available-now-could-be-final-beta/)

来源：OS X Daily

发布时间：2024-08-21 05:02:25

iOS 18 beta 7 和 iPadOS 18 beta 7 已向 iOS 和 iPadOS 开发者测试计划中的用户发布。与第 7 个开发者测试版相匹配的是第 5 个公开测试版，也已推出。除了尚未公开的功能外，iOS 18 beta 7 可能就是最终的测试版。

## iOS Blog

### [🎉 SwiftNIO Oblivious HTTP：保护隐私的 HTTP 协议](https://swift.org/blog/introducing-swift-nio-oblivious-http/)

来源：Swift.org

发布时间：2024-08-21 18:00:00

SwiftNIO Oblivious HTTP 是一种新的软件包，它为 Swift 生态系统引入了对 Oblivious HTTP 的临时支持。Oblivious HTTP 是一种协议，允许客户端向服务器发出请求，而服务器无法识别这些请求的来源。与传统的 HTTP 请求不同，Oblivious HTTP 提供了一种安全机制来保护客户端身份信息，方法是将 HTTP 消息加密与受信任的第三方中继服务相结合，从而在不产生显着性能开销的情况下为用户提供更高的隐私性。

### [🤔 解决 Swift 6 中的“Task-isolated value of type ‘() async -> Void’ passed as a strongly transferred parameter”错误](https://www.donnywals.com/solving-task-isolated-value-of-type-async-void-passed-as-a-strongly-transferred-parameter/)

来源：Donny Wals

发布时间：2024-08-21 16:38:51

在 Swift 6 中开启严格并发模式后，可能会遇到“Task-isolated value of type ‘() async -> Void’ passed as a strongly transferred parameter”错误。这通常是因为在任务中捕获了不可发送的对象，导致可能的数据竞争。解决方法包括使捕获类型可发送或使用演员，或在子任务外部修改数组。

### [🤯 在 Swift 中同步调用 Swift 并发异步代码](https://wadetregaskis.com/calling-swift-concurrency-async-code-synchronously-in-swift/)

来源：Wade Tregaskis

发布时间：2024-08-21 08:09:00

有时你只需要把一个圆钉塞进一个方孔里。有时这确实是最好的选择（或者更准确地说：最不坏的选择）。我发现我经常被我无法控制的 API 强制执行（最常见的是 Apple 的 API）。例如，数据源或委托回调是同步的，并且需要...

### [🎉 iOS 开发者必备：App Store 优化指南](https://juejin.cn/post/7405158681089736716)

来源：掘金 iOS

发布时间：2024-08-21 11:02:19

本文提供了 App Store 优化的全面指南，涵盖了从应用图标设计到关键词优化、评论管理等各个方面，帮助开发者提升应用在 App Store 中的排名和曝光度。

## Tech News

### [🤖️人工智能基础设施的未来](https://engineering.fb.com/2024/08/20/data-infrastructure/aparna-ramani-future-of-ai-infrastructure-meta/)

来源：Engineering at Meta

发布时间：2024-08-21 00:00:26

大规模交付新的人工智能技术也意味着重新思考我们基础设施的每一层——从硅和软件系统，甚至我们的数据中心设计。连续第二年，Meta 的工程和基础设施团队参加了 AI Infra @ Scale 会议，他们在会上讨论了扩大 [...]

### [💡企业治理中人工智能的使用必须在董事会层面得到改善](https://www.artificialintelligence-news.com/news/use-ai-business-governance-must-improve-at-board-level/)

来源：AI News

发布时间：2024-08-21 00:58:43

挪威主权财富基金的首席治理和合规官卡琳·史密斯·伊赫纳乔表示，董事会需要熟练使用人工智能，并控制其在企业中的应用以降低风险。挪威银行投资基金在全球近 9,000 家公司中持有大量股份，占全球股票总量的 1.3%，管理着价值 1.7 万亿美元的资产。

### [🎉 GitHub 安全配置新增非提供商模式的密钥扫描](https://github.blog/changelog/2024-08-20-secret-scanning-non-provider-patterns-are-included-in-security-configurations)

来源：GitHub Changelog

发布时间：2024-08-21 04:37:58

GitHub 安全配置现已包含非提供商模式的密钥扫描，这将使你能够在代码中查找和修复更多类型的机密。

## Daily Code

### [The Composable Architecture 🧩](https://github.com/pointfreeco/swift-composable-architecture)

来源：Trending Swift repositories on GitHub today · GitHub

发布时间：2024-08-22 08:34:20

The Composable Architecture (TCA, for short) is a library for building applications in a consistent and understandable way, with composition, testing, and ergonomics in mind. It can be used in SwiftUI, UIKit, and more, and on any Apple platform (iOS, macOS, visionOS, tvOS, and watchOS).

This library provides a few core tools that can be used to build applications of varying purpose and complexity. It provides compelling stories that you can follow to solve many problems you encounter day-to-day when building applications, such as:

- State management
- Composition
- Side effects
- Testing
- Ergonomics

### [⚡️ 高性能 JavaScript 实用程序库：es-toolkit](https://github.com/toss/es-toolkit)

来源：Trending repositories on GitHub today · GitHub

发布时间：2024-08-22 05:08:18

es-toolkit 是一款最先进的高性能 JavaScript 实用程序库，具有较小的包大小和强大的类型注释。它提供各种日常实用功能，如防抖、延迟、分块、求和和选择。es-toolkit 在设计时考虑了性能，在现代 JavaScript 环境中实现了 2-3 倍的性能提升。
