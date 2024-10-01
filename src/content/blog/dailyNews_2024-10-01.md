---
title: "Daily News #2024-10-01"
date: "2024-10-01 08:48:28"
description: "🏠 HomePod 带显示屏和 homeOS 将于明年推出
🌟Swift 测试中的 #expect 宏
🌟 使用 Hummingbird 构建代理服务器
🌈 网格渐变：SwiftUI 的新特性
VisionOS 30 天学习计划
❄️ 冷酷的数据科学如何利用 Wolfram Research 驾驭人工智能"
tags: 
- 'Swift'
- 'Hummingbird'
- 'SwiftUI'
- '人工智能'
- '智能家居'
- 'VisionOS'

---

> - 🏠 HomePod 带显示屏和 homeOS 将于明年推出
> - 🌟Swift 测试中的 #expect 宏
> - 🌟 使用 Hummingbird 构建代理服务器
> - 🌈 网格渐变：SwiftUI 的新特性
> - VisionOS 30 天学习计划
> - ❄️ 冷酷的数据科学如何利用 Wolfram Research 驾驭人工智能

## Apple News

### [🏠 HomePod 带显示屏和 homeOS 将于明年推出](https://9to5mac.com/2024/09/29/homepod-with-display-homeos-ai/)

来源：Hacker News - Newest: "apple"

发布时间：2024-09-30 04:04:41

苹果公司计划明年推出两款 HomePod 带显示屏，其中一款将配备机械臂和更大的显示屏。这两款设备都将支持 Apple Intelligence，并运行新的操作系统 homeOS。

## iOS Blog

### [🌟Swift 测试中的 #expect 宏](https://www.avanderlee.com/swift-testing/expect-macro/)

来源：SwiftLee

发布时间：2024-09-30 19:46:30

Swift 测试是 Apple 用于编写测试的 Swift 框架，它引入了多个宏，包括 #expect 宏。在过去，我们不得不使用各种 XCAssert 变体，现在我们可以依赖一个功能强大的替代品，它将帮助我们更快地调试测试。

### [🌟 使用 Hummingbird 构建代理服务器](https://swiftonserver.com/how-to-build-a-proxy-server-with-hummingbird/)

来源：Swift on server

发布时间：2024-09-30 16:00:00

Hummingbird 的异步和灵活性特性让你可以非常轻松地创建 HTTP 代理。要创建代理服务器，你可以使用三种方法来拦截传入请求：第一种方法是在路由器上创建路由，例如，使用（递归）通配符。与这些路径关联的路由将接收此请求。然后，它可以修改目标服务器并将请求转发到那里。第二种解决方案是创建一个拦截请求的路由器中间件。这可以应用于路由组或全局应用于所有请求。最后，你可以通过在自定义 HTTP 响应器中拦截所有请求来转发每个请求。每种解决方案都需要导入必要的模块：以上每种解决方案都以相同的方式转发请求。实际的转发逻辑仅针对每种解决方案以不同的方式调用。要转发请求，你需要创建一个由 AsyncHTTPClient 库定义的新 HTTPClientRequest。然后，将目标主机（你的 API）换成新主机。然后，你可以使用 HTTPClient 发送请求并接收响应。此函数中的 HTTP 客户端是可以互换的，但本教程的其余部分将使用 HTTPClient.shared。如你所见，转发请求有四个步骤：修改传入请求的 URL、方法和标头以指向目标服务器。以流式方式将请求的 RequestBody 提供给 HTTPClient。使用 HTTPClient 执行请求。将响应转发回最终用户。在步骤 2 和步骤 4 中，HTTP 正文作为流或具体来说是 AsyncSequence<ByteBuffer> 传递。这允许 SwiftNIO 有效地传递数据，同时在两个方向（客户端和远程）应用反压。AsyncSequence<ByteBuffer> 由于 Hummingbird 的设计，其中正文总是流式传输，这不仅是一种高效的解决方案，而且也是最容易实现的。第一个选项是在路由器上创建一个路由，该路由将拦截请求并将其转发到目标服务器。由于代码与前面的示例相同，因此我们只需要从此中间件中调用转发函数。转发对于第二个选项，你需要创建一个新的路由器中间件。此中间件将拦截请求并将其转发到目标服务器。然后，一旦中间件设置好，你就可以将 Router.add(middleware:) 添加到路由器。最后一个选项将实现一个 HTTP 响应器。然后，你可以在应用程序中设置响应器。Hummingbird 的强大设计使得轻松地将数据流入和流出你的应用程序成为可能。这使其成为创建代理服务器的绝佳选择。本教程中介绍的三个解决方案中的每一个都可以用来使用 Hummingbird 创建代理服务器。选择最适合你需求的那个，享受 Hummingbird 的强大功能。

### [🌈 网格渐变：SwiftUI 的新特性](https://fatbobman.com/zh/weekly/issue-051/)

来源：肘子的 Swift 记事本 ｜ Fatbobman's Blog

发布时间：2024-09-30 22:00:00

网格渐变是一种在 WWDC24 上推出的 SwiftUI 新特性，允许在一个网格中展示动态颜色范围。本文详细介绍了网格渐变的用法和注意事项，帮助开发者理解和使用这一新特性。作者指出，网格渐变可以得体地应用以增强 UI 效果，也可能因使用不当而产生负面影响。

### [VisionOS 30 天学习计划](https://github.com/SwiftOldDriver/iOS-Weekly/releases/tag/%23307)

来源：Release notes from iOS-Weekly

发布时间：2024-09-30 15:04:03

这个计划目前有两个版本：visionOS 1.0 以及 visionOS 2.0 版本。这里面可以找到大部分 visionOS 特性相关的示例代码，可以快速尝试 visionOS 上的独特的特性。十分推荐都看一遍，可以帮组你快速上手 visionOS 。

## Tech News

### [❄️ 冷酷的数据科学如何利用 Wolfram Research 驾驭人工智能](https://www.artificialintelligence-news.com/news/how-cold-hard-data-science-harnesses-ai-with-wolfram-research/?utm_source=rss&utm_medium=rss&utm_campaign=how-cold-hard-data-science-harnesses-ai-with-wolfram-research)

来源：AI News

发布时间：2024-09-30 22:34:30

文章介绍了 Wolfram Research 如何利用人工智能来增强其数据科学平台，使研究人员和数据科学家能够更有效地分析和可视化数据。它强调了 Wolfram Alpha 的自然语言处理功能，以及 Wolfram Mathematica 中用于机器学习和深度学习的工具。
