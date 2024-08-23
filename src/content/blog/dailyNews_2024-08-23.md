---
title: "Daily News #2024-08-23"
date: "2024-08-23 08:35:30"
description: "💻 史蒂夫·乔布斯 Apple-1 电脑即将拍卖，预计创纪录
🎉欧盟用户迎来iOS新变化：浏览器选择、默认应用和应用删除
🌟iOS 18、iPadOS 18、macOS Sequoia 第 5 个公测版现已推出
📱 在苹果设备上运行 Stable Diffusion
🌟 如何设置 SPM 包的 Swift 语言模式
🤯 NSPasteboard 崩溃，原因是处理文件 Promise 时内部并发内存突变不安全
🎉 OpenAI发布GPT-4o微调功能
🔥Meta发布Llama 3，开放式LLM新标杆
🌟 GitHub Secret 扫描现已对非提供程序模式进行去重
🚀 Swift 算法：序列和集合算法集合
⚡️ uv: 速度极快的 Python 包和项目管理器"
tags: 
- 'iOS 18'
- 'GPT-4'
- 'Python'
- '欧盟'
- 'AI'
- 'iOS'
- 'Swift'
- 'Apple-1'
- '安全'
- '机器学习'

---

> - 💻 史蒂夫·乔布斯 Apple-1 电脑即将拍卖，预计创纪录
> - 🎉欧盟用户迎来iOS新变化：浏览器选择、默认应用和应用删除
> - 🌟iOS 18、iPadOS 18、macOS Sequoia 第 5 个公测版现已推出
> - 📱 在苹果设备上运行 Stable Diffusion
> - 🌟 如何设置 SPM 包的 Swift 语言模式
> - 🤯 NSPasteboard 崩溃，原因是处理文件 Promise 时内部并发内存突变不安全
> - 🎉 OpenAI发布GPT-4o微调功能
> - 🔥Meta发布Llama 3，开放式LLM新标杆
> - 🌟 GitHub Secret 扫描现已对非提供程序模式进行去重
> - 🚀 Swift 算法：序列和集合算法集合
> - ⚡️ uv: 速度极快的 Python 包和项目管理器

## Apple News

### [💻 史蒂夫·乔布斯 Apple-1 电脑即将拍卖，预计创纪录](https://newatlas.com/technology/steve-jobs-apple-1-auction/)

来源：Hacker News - Newest: "apple"

发布时间：2024-08-22 08:19:43

史蒂夫·乔布斯拥有的 Apple-1 电脑将于 9 月 12 日在纽约佳士得拍卖行拍卖，预计将创下拍卖纪录。该电脑是苹果公司成立的标志，也是乔布斯个人使用过的机器，同时也是已故微软联合创始人保罗·艾伦科技收藏的一部分。

### [🎉欧盟用户迎来iOS新变化：浏览器选择、默认应用和应用删除](https://developer.apple.com/news/?id=zglax7gc)

来源：Latest News - Apple Developer

发布时间：2024-08-22 22:00:36

欧盟用户将迎来iOS新变化，包括浏览器选择屏幕、默认应用和应用删除。浏览器选择屏幕将提供更多浏览器信息，用户可以设置更多默认应用，包括拨号、短信、翻译、导航、密码管理、键盘和呼叫垃圾邮件过滤器。此外，App Store、信息、照片、相机和Safari应用现在可以被欧盟用户删除。

### [🌟iOS 18、iPadOS 18、macOS Sequoia 第 5 个公测版现已推出](https://osxdaily.com/2024/08/21/public-beta-5-of-ios-18-macos-sequoia-ipados-18-available-for-testing/)

来源：OS X Daily

发布时间：2024-08-22 05:06:33

苹果已发布 iOS 18、iPadOS 18 和 macOS Sequoia 的第 5 个公测版。第 5 个公测版版本与第 7 个开发者测试版版本相同。有传言称 iOS 18 开发者测试版 7（因此还有 iOS 18 公测版 5）是 iOS 18.0 的最终测试版。

## iOS Blog

### [📱 在苹果设备上运行 Stable Diffusion](https://juejin.cn/post/7405770868506509327)

来源：掘金 iOS

发布时间：2024-08-22 16:03:53

文章提供了在苹果设备上运行 Stable Diffusion 模型的详细指南，包括模型下载、格式转换和 Swift 中的调用方法。对机器学习和图像生成感兴趣的开发者值得一读。

### [🌟 如何设置 SPM 包的 Swift 语言模式](https://www.donnywals.com/setting-the-swift-language-mode-for-an-spm-package/)

来源：Donny Wals

发布时间：2024-08-22 01:59:32

在 Xcode 16 中创建新的 Swift 包时，Package.swift 的内容可能如下所示：

```
s// swift-tools-version: 6.0
// The swift-tools-version declares the minimum version of Swift required to build this package.

import PackageDescription

let package = Package(
    name: "AppCore",
    products: [
        // Products define the executables and libraries a package produces, making them visible to other packages.
        .library(
            name: "AppCore",
            targets: ["AppCore"])
    ],
    targets: [
        // Targets are the basic building blocks of a package, defining a module or a test suite.
        // Targets can depend on other targets in this package and products from dependencies.
        .target(
            name: "AppCore"
        )
    ]
)
```

请注意，该软件包的 Swift 工具版本设置为 6.0。例如，如果你希望你的项目引用 iOS18，则需要将 Swift 工具版本设置为 6.0。这样做的副作用是你的软件包现在将以 Swift 6 语言模式构建。这意味着你将在软件包中获得 Swift 的完整可发送性和并发性检查套件，并且编译器会将任何问题标记为错误。

你可能还没有准备好在新软件包中使用 Swift 6.0。在这些情况下，如果你不使用 6.0 工具链中的任何功能，你可以将 Swift 工具版本设置回 5.10，或者可以在保留 6.0 工具链的同时将软件包的语言模式设置为 Swift 5：

```
s// swift-tools-version: 6.0
// The swift-tools-version declares the minimum version of Swift required to build this package.

import PackageDescription

let package = Package(
    name: "AppCore",
    platforms: [.iOS(.v18)],
    // ... the rest of the package description
    swiftLanguageModes: [.v5]
)
```

你还可以为软件包中的特定目标分配 swift 语言模式。如下所示：

```
targets: [
  // Targets are the basic building blocks of a package, defining a module or a test suite.
  // Targets can depend on other targets in this package and products from dependencies.
  .target(
    name: "AppCore",
    swiftSettings: [.swiftLanguageMode(.v5)]
  )
]
```

通过使用 Swift 5 语言模式，你可以像往常一样继续编写代码，直到你准备好开始迁移到 Swift 6。例如，你可能希望首先启用严格的并发性检查。

### [🤯 NSPasteboard 崩溃，原因是处理文件 Promise 时内部并发内存突变不安全](https://wadetregaskis.com/nspasteboard-crashes-due-to-unsafe-internal-concurrent-memory-mutation-when-handling-file-promises/)

来源：Wade Tregaskis

发布时间：2024-08-22 13:01:02

NSPasteboard 在主线程和全局并发调度池中同时修改自身，涉及到其内部类型缓存。这意外地简单... 继续阅读

## Tech News

### [🎉 OpenAI发布GPT-4o微调功能](https://www.artificialintelligence-news.com/news/openai-delivers-gpt-4o-fine-tuning/)

来源：AI News

发布时间：2024-08-22 00:18:17

OpenAI宣布为其GPT-4o模型发布微调功能，允许开发者使用自定义数据集对模型进行微调，从而提高特定应用的性能并降低成本。

### [🔥Meta发布Llama 3，开放式LLM新标杆](https://engineering.fb.com/2024/08/21/production-engineering/bringing-llama-3-to-life/)

来源：Engineering at Meta

发布时间：2024-08-22 00:00:49

Meta发布了其迄今为止功能最强大的开放式LLM Llama 3，以及最新发布的Llama 3.1，它将支持新的工作流，例如合成数据生成和模型蒸馏，具有无与伦比的灵活性和控制力，以及与最佳闭源模型媲美的最先进功能。

### [🌟 GitHub Secret 扫描现已对非提供程序模式进行去重](https://github.blog/changelog/2024-08-22-secret-scanning-non-provider-pattern-deduplication)

来源：GitHub Changelog

发布时间：2024-08-22 23:47:56

GitHub Secret 扫描现已对非提供程序模式进行去重，这意味着它现在可以更有效地识别和标记存储库中的秘密。这将有助于提高扫描的准确性和效率，从而使开发人员更容易保护其代码和数据。

## Daily Code

### [🚀 Swift 算法：序列和集合算法集合](https://github.com/apple/swift-algorithms)

来源：Trending Swift repositories on GitHub today · GitHub

发布时间：2024-08-23 06:35:52

Swift Algorithms 是一个序列和集合算法的开源包，以及它们相关的类型。Algorithms 包提供了各种序列和集合操作，允许您循环遍历集合的元素，查找组合和排列，创建随机样本等等。

### [⚡️ uv: 速度极快的 Python 包和项目管理器](https://github.com/astral-sh/uv)

来源：Trending repositories on GitHub today · GitHub

发布时间：2024-08-23 06:29:54

uv 是一款极其快速的 Python 包和项目管理器，用 Rust 编写。它可以取代 pip、conda、virtualenv、poetry、flit、hatch 和 pex 等多个工具，速度比 pip 快 10-100 倍。uv 可以安装和管理 Python 版本，运行和安装 Python 应用程序，运行单文件脚本（支持内联依赖元数据），提供全面的项目管理，并具有通用的锁定文件。它还包括一个与 pip 兼容的接口，可以在熟悉的 CLI 中获得性能提升。uv 支持 Cargo 风格的工作区，适用于可扩展项目。它具有磁盘空间效率，并具有用于依赖项去重的全局缓存。uv 可以通过 Cargo、pip 或 conda 安装，支持 macOS、Linux 和 Windows。
