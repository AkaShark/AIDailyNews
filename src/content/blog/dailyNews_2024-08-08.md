---
title: "Daily News #2024-08-08"
date: "2024-08-08 08:35:39"
description: "📣 iOS 18、macOS Sequoia、iPadOS 18 公测版 3 发布
🌟 SwiftUI 布局异常：分析思路与解决策略
解决 Swift 中 @Sendable 闭包中“捕获不可发送类型”的问题
Flutter动画之DynamicWidget
💡 区块链可以解决垄断的 AI 生态系统
🎉 Copilot 订阅网络路由更新发布计划
Swift 集合：Swift 编程语言的数据结构实现"
tags: 
- 'iOS'
- 'Copilot'
- '数据结构'
- 'Swift'
- 'AI 生态系统'
- 'SwiftUI'
- 'Flutter'

---

> - 📣 iOS 18、macOS Sequoia、iPadOS 18 公测版 3 发布
> - 🌟 SwiftUI 布局异常：分析思路与解决策略
> - 解决 Swift 中 @Sendable 闭包中“捕获不可发送类型”的问题
> - Flutter动画之DynamicWidget
> - 💡 区块链可以解决垄断的 AI 生态系统
> - 🎉 Copilot 订阅网络路由更新发布计划
> - Swift 集合：Swift 编程语言的数据结构实现

## Apple News

### [📣 iOS 18、macOS Sequoia、iPadOS 18 公测版 3 发布](https://osxdaily.com/2024/08/06/public-beta-3-of-ios-18-macos-sequoia-ipados-18-available-for-testing/)

来源：OS X Daily

发布时间：2024-08-07 05:00:44

苹果公司向参与公测计划的用户发布了 iOS 18、macOS Sequoia 和 iPadOS 18 的第三个公测版。这些公测版与前一天发布的第五个开发者测试版相匹配。对于那些参与公测计划的用户，还有 tvOS 18 和 watchOS 11 的新公测版。

## iOS Blog

### [🌟 SwiftUI 布局异常：分析思路与解决策略](https://fatbobman.com/zh/posts/analysis-approach-and-resolution-strategies-for-swiftui-layout-issues/)

来源：肘子的 Swift 记事本 ｜ Fatbobman's Blog

发布时间：2024-08-07 22:12:00

本文通过剖析一个 Grid 布局异常的案例，探讨在日常 SwiftUI 开发中遇到问题时的分析思路和解决策略，并介绍了 LayoutMonitor 工具的使用方法，帮助开发者系统地思考、假设、验证和调试复杂的布局问题。

### [解决 Swift 中 @Sendable 闭包中“捕获不可发送类型”的问题](https://www.donnywals.com/solving-capture-of-non-sendable-type-in-sendable-closure-in-swift/)

来源：Donny Wals

发布时间：2024-08-07 17:28:12

在 Swift 6 中使用严格并发模式时，可能会遇到“捕获不可发送类型”的警告。这表示在闭包中捕获并使用了属性，而该闭包标记为 @Sendable，这意味着它将在并发环境中运行。编译器警告我们，由于此闭包将并发运行，因此我们应确保在该闭包中捕获的任何属性都可以安全地从并发代码中使用。解决此问题的一种方法是确保 TaskCompletion 闭包是 @Sendable，以便编译器知道我们可以安全地跨并发边界传递该闭包。

### [Flutter动画之DynamicWidget](https://juejin.cn/post/7399984522093838363)

来源：掘金 iOS

发布时间：2024-08-07 01:07:18

本文主要介绍了Flutter中DynamicWidget的使用，通过示例代码展示了如何使用DynamicWidget实现动画效果，文章内容清晰易懂，适合有一定Flutter基础的开发者阅读。

## Tech News

### [💡 区块链可以解决垄断的 AI 生态系统](https://www.artificialintelligence-news.com/news/blockchain-could-solve-the-monopolised-ai-ecosystem/)

来源：AI News

发布时间：2024-08-07 22:25:19

AI 产业一直是人类的“未来主义观点”，无论是在电影、卡通还是现实生活中。计算机代表未来主义的人类工作、思考和行动——好吧，除了沙丘电影。在过去五年中，人工智能已成为世界上最热门的话题，仅次于 Covid 19...

### [🎉 Copilot 订阅网络路由更新发布计划](https://github.blog/changelog/2024-08-06-revised-release-plan-for-copilot-subscription-based-network-routing)

来源：Changelogs Archive - The GitHub Blog

发布时间：2024-08-07 06:30:32

Copilot 订阅网络路由更新发布计划，提供更灵活的网络配置和更低的成本。该更新将于 2024 年 8 月 15 日正式发布，届时用户可以根据自己的需求选择合适的订阅套餐。

## Daily Code

### [Swift 集合：Swift 编程语言的数据结构实现](https://github.com/apple/swift-collections)

来源：Trending Swift repositories on GitHub today · GitHub

发布时间：2024-08-08 05:48:52

Swift Collections 是一个开源包，为 Swift 编程语言提供数据结构实现。该包目前提供以下实现：动态位集合、双端队列、最小最大堆、有序集合、哈希集合、持久哈希集合。Swift Collections 使用与 Swift Numerics 相同的模块化方法：为其实现的每个主题数据结构组提供一个独立的模块。该包是源稳定的，公共 API 的版本号遵循语义版本控制。
