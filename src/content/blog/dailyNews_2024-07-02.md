---
title: "Daily News #2024-07-02"
date: "2024-07-02 08:34:28"
description: "🎉欧盟App Store支持替代支付
🤯 CocoaPods 漏洞暴露数百万设备长达十年
🎉 Swift 6 来了，数据竞态安全检查了解一下
🎉 SwiftUI 滚动几何和位置视图修改器
🌟 老司机 iOS 周报 #295
💡 完善 SwiftUI 生命周期管理：AppPhase API 建议
🤔欧盟调查微软-OpenAI和谷歌-三星的AI交易
🔒 Signal iOS：注重隐私的开源即时通讯应用
💻 ImHex: 一款适用于逆向工程师、程序员和重视视力的十六进制编辑器"
tags: 
- 'SwiftUI'
- 'iOS'
- '工具'
- '反垄断'
- '安全漏洞'
- '苹果'
- '隐私'
- 'Swift'
- '欧盟'
- '即时通讯'

---

> - 🎉欧盟App Store支持替代支付
> - 🤯 CocoaPods 漏洞暴露数百万设备长达十年
> - 🎉 Swift 6 来了，数据竞态安全检查了解一下
> - 🎉 SwiftUI 滚动几何和位置视图修改器
> - 🌟 老司机 iOS 周报 #295
> - 💡 完善 SwiftUI 生命周期管理：AppPhase API 建议
> - 🤔欧盟调查微软-OpenAI和谷歌-三星的AI交易
> - 🔒 Signal iOS：注重隐私的开源即时通讯应用
> - 💻 ImHex: 一款适用于逆向工程师、程序员和重视视力的十六进制编辑器

## Apple News

### [🎉欧盟App Store支持替代支付](https://developer.apple.com/news/?id=7caa5bf5)

来源：Latest News - Apple Developer

发布时间：2024-07-01 21:00:58

欧盟地区App Store的应用现已支持替代支付方式，开发者可以集成非苹果支付渠道，为用户提供更多选择。

### [🤯 CocoaPods 漏洞暴露数百万设备长达十年](https://www.darkreading.com/cloud-security/apple-cocoapods-bugs-expose-apps-code-injection)

来源：Hacker News - Newest: "apple"

发布时间：2024-07-01 22:45:05

CocoaPods 中的严重依赖管理供应链漏洞在近十年内使数百万设备面临任意恶意软件的风险。该漏洞与 RubyGem 中的一个最大严重性远程代码执行漏洞有关，但由于其难以发现，因此被忽视了很长时间。

## iOS Blog

### [🎉 Swift 6 来了，数据竞态安全检查了解一下](https://swift.org/blog/ready-for-swift-6/)

来源：Swift.org

发布时间：2024-07-01 17:00:00
![](https://www.swift.org/assets/images/ready-for-swift-6-blog/packages-with-no-data-race-errors.png)
Swift 6 引入了编译时数据竞态安全检查，可以消除潜在的并发错误，提升代码安全性。文章介绍了 Swift 6 的数据竞态安全检查功能，以及如何跟踪 Swift 6 的就绪性和进度。还提供了如何采用 Swift 6 语言模式的号召性用语。

### [🎉 SwiftUI 滚动几何和位置视图修改器](https://augmentedcode.io/2024/07/01/scroll-geometry-and-position-view-modifiers-in-swiftui-on-ios-18/)

来源：Blog – Augmented Code

发布时间：2024-07-01 23:00:00

WWDC'24 对滚动进行了一些更新。其中之一是 onScrollGeometryChange(for:of:action:)，我们可以用它来响应滚动几何变化。视图修改器有两个闭包，第一个闭包将滚动几何转换为我们喜欢的任意可等同类型。如果该值发生变化，则调用操作闭包。

### [🌟 老司机 iOS 周报 #295](https://github.com/SwiftOldDriver/iOS-Weekly/releases/tag/%23295)

来源：Release notes from iOS-Weekly

发布时间：2024-07-01 12:48:03

本期周报包含了 WWDC24 内参、新手推荐、文章、工具、代码和内推等内容，涵盖了 Swift Testing、Flutter 异步机制、Apple 公共框架、Photos 搜索界面逆向工程、应用图标设计、SwiftData 与 Realm 性能对比、AI 文件整理工具、macOS Sequoia 测试版安装、App Store 服务器 Swift 库、ARM64 汇编语言学习等主题，为 iOS 开发者提供了丰富的资讯和资源。

### [💡 完善 SwiftUI 生命周期管理：AppPhase API 建议](https://fatbobman.com/zh/weekly/issue-038/)

来源：肘子的 Swift 记事本 ｜ Fatbobman's Blog

发布时间：2024-07-01 22:00:00

SwiftUI 引入了 ScenePhase API 表示应用生命周期状态，但存在局限性。本文建议开发一个更全面的 AppPhase API，以便于窗口场景事件分离，独立管理应用级的生命周期事件。作者指出，当前的 ScenePhase API 过度依赖窗口管理，未能全面覆盖应用状态的变化。

## Tech News

### [🤔欧盟调查微软-OpenAI和谷歌-三星的AI交易](https://www.artificialintelligence-news.com/2024/07/01/eu-probes-microsoft-openai-and-google-samsung-ai-deals/)

来源：AI News

发布时间：2024-07-01 21:09:57

欧盟正在调查微软与 OpenAI 以及谷歌与三星之间的 AI 交易，以确保这些交易不会损害竞争。欧盟委员会执行副主席玛格丽特·维斯塔格表示，人工智能正在“以惊人的速度发展”，并透露正在对各种与人工智能相关的市场行为进行多项初步调查。

## Daily Code

### [🔒 Signal iOS：注重隐私的开源即时通讯应用](https://github.com/signalapp/Signal-iOS)

来源：Trending Swift repositories on GitHub today · GitHub

发布时间：2024-07-02 07:18:28

Signal 是一款免费、开源的即时通讯应用，注重隐私保护，提供端到端加密的消息、语音和视频通话，还支持群组聊天和文件共享，是一款安全可靠的通讯工具。

### [💻 ImHex: 一款适用于逆向工程师、程序员和重视视力的十六进制编辑器](https://github.com/WerWolv/ImHex)

来源：Trending repositories on GitHub today · GitHub

发布时间：2024-07-02 05:22:28

ImHex是一款功能强大的十六进制编辑器，专为逆向工程师、程序员和重视视力的人员设计。它具有强大的十六进制视图、自定义的类似C++的模式语言、主题支持、导入和导出数据以及数据搜索等功能。
