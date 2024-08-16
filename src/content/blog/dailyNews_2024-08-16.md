---
title: "Daily News #2024-08-16"
date: "2024-08-16 08:35:21"
description: "🌟 怀旧的 Stapler 回归 Mac，让你轻松管理项目
🎉 Apple Card 连续四年获评无年费联名信用卡客户满意度第一
🌟 解决 Swift 中“引用 var myVariable 不安全，因为它涉及共享可变状态”
🎉 使用 SwiftUI 构建自定义二维码扫描仪
🌟Meta如何大规模制作AI生成图像动画
🌟谷歌Pixel 9智能手机：移动AI的重大进步
✨ Copilot 现可帮助修复失败的 Actions 作业
🌟 Kingfisher：一款强大的 Swift 图片下载和缓存库"
tags: 
- '图片下载'
- 'SwiftUI'
- 'AI'
- 'Swift'
- '代码'
- '信用卡'
- '怀旧'

---

> - 🌟 怀旧的 Stapler 回归 Mac，让你轻松管理项目
> - 🎉 Apple Card 连续四年获评无年费联名信用卡客户满意度第一
> - 🌟 解决 Swift 中“引用 var myVariable 不安全，因为它涉及共享可变状态”
> - 🎉 使用 SwiftUI 构建自定义二维码扫描仪
> - 🌟Meta如何大规模制作AI生成图像动画
> - 🌟谷歌Pixel 9智能手机：移动AI的重大进步
> - ✨ Copilot 现可帮助修复失败的 Actions 作业
> - 🌟 Kingfisher：一款强大的 Swift 图片下载和缓存库

## Apple News

### [🌟 怀旧的 Stapler 回归 Mac，让你轻松管理项目](https://osxdaily.com/2024/08/14/launch-all-apps-documents-related-to-a-project-with-stapler-for-mac/)

来源：OS X Daily

发布时间：2024-08-15 03:42:33

Stapler 是一款经典的 Mac 应用程序，它可以将一系列应用程序和文档分组到一个文档中，当打开该文档时，它将启动所有这些文档及其各自的程序。这比在文件中四处挖掘要容易得多。

### [🎉 Apple Card 连续四年获评无年费联名信用卡客户满意度第一](https://www.apple.com/newsroom/2024/08/apple-card-named-best-in-customer-satisfaction-by-jd-power/)

来源：Apple Newsroom

发布时间：2024-08-15 21:59:05

Apple Card 凭借其无年费、易于使用和安全可靠的特点，连续四年荣获 J.D. Power 美国信用卡满意度研究中无年费联名信用卡客户满意度第一的殊荣。Apple Card 还提供高达 3% 的每日返现，并支持家庭共享和储蓄账户功能，为用户提供便捷的理财体验。

## iOS Blog

### [🌟 解决 Swift 中“引用 var myVariable 不安全，因为它涉及共享可变状态”](https://www.donnywals.com/solving-reference-to-var-myvariable-is-not-concurrency-safe-because-it-involves-shared-mutable-state-in-swift/)

来源：Donny Wals

发布时间：2024-08-15 17:50:01

在 Swift 6 中，开启严格并发模式后，可能会遇到“引用 var myVariable 不安全，因为它涉及共享可变状态”的警告。这是因为编译器认为任何全局可访问的 var 从并发角度来看都是不安全的。为了解决这个问题，可以将 myVariable 移到一个 actor 中，或者将其隔离到一个全局 actor 中。如果确定共享的可变状态没有问题，可以使用 nonisolated(unsafe) 来告诉编译器忽略警告。

### [🎉 使用 SwiftUI 构建自定义二维码扫描仪](https://juejin.cn/post/7402915897906298895)

来源：掘金 iOS

发布时间：2024-08-15 15:33:49

本文介绍了如何使用 SwiftUI 构建一个自定义的二维码扫描仪。它涵盖了创建自定义的 UIViewControllerRepresentable 来使用 AVCaptureSession 扫描二维码的步骤。

## Tech News

### [🌟Meta如何大规模制作AI生成图像动画](https://engineering.fb.com/2024/08/14/production-engineering/how-meta-animates-ai-generated-images-at-scale/)

来源：Engineering at Meta

发布时间：2024-08-15 05:20:04

Meta AI旨在让人们通过生成式AI（GenAI）获得更高的生产力和创造力。但GenAI也面临着规模上的挑战。在Meta部署新的GenAI技术时，我们还专注于尽可能快且高效地向人们提供这些服务。本文介绍了Meta如何大规模制作AI生成图像动画。

### [🌟谷歌Pixel 9智能手机：移动AI的重大进步](https://www.artificialintelligence-news.com/news/google-advances-mobile-ai-pixel-9-smartphones/)

来源：AI News

发布时间：2024-08-15 18:36:43

谷歌发布了新一代Pixel 9智能手机，强调了其增强的AI功能。与往常不同的是，谷歌此次提前发布了新机，通常情况下，谷歌会在秋季发布新一代Pixel机型。然而，与前代机型相比，新机型的变化可谓翻天覆地。新智能手机更深入地集成了...

### [✨ Copilot 现可帮助修复失败的 Actions 作业](https://github.blog/changelog/2024-08-15-copilot-enterprise-now-helps-you-fix-failed-actions-jobs-plus-other-august-updates-public-beta)

来源：GitHub Changelog

发布时间：2024-08-15 23:16:32

Copilot Enterprise 现可帮助您修复失败的 Actions 作业，并提供其他 8 月更新（公开测试版）。

## Daily Code

### [🌟 Kingfisher：一款强大的 Swift 图片下载和缓存库](https://github.com/onevcat/Kingfisher)

来源：Trending Swift repositories on GitHub today · GitHub

发布时间：2024-08-16 06:51:40

Kingfisher 是一个功能强大的纯 Swift 库，用于从网络下载和缓存图像。它提供了一种纯 Swift 的方式，让你在下一个应用程序中使用远程图像。
