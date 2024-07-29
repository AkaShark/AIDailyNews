---
title: "Daily News #2024-07-29"
date: "2024-07-29 08:35:53"
description: "🎉 报道：苹果开始认真研发可折叠 iPhone
🌟 乔布斯 1983 年演讲视频曝光
Flutter初探之渲染管道（二）
MinerU：基于 PDF-Extract-Kit 的 PDF 解析工具，支持 PDF 转 Markdown
🌟 UTM：在 iOS 和 macOS 上运行 Windows、Linux 和更多内容"
tags: 
- 'PDF 解析'
- 'Flutter'
- '虚拟机'
- '苹果'
- '模拟器'
- '可折叠手机'

---

> - 🎉 报道：苹果开始认真研发可折叠 iPhone
> - 🌟 乔布斯 1983 年演讲视频曝光
> - Flutter初探之渲染管道（二）
> - MinerU：基于 PDF-Extract-Kit 的 PDF 解析工具，支持 PDF 转 Markdown
> - 🌟 UTM：在 iOS 和 macOS 上运行 Windows、Linux 和更多内容

## Apple News

### [🎉 报道：苹果开始认真研发可折叠 iPhone](https://arstechnica.com/gadgets/2024/07/report-apple-begins-serious-work-on-a-foldable-iphone/)

来源：Hacker News - Newest: "apple"

发布时间：2024-07-28 04:11:45

据科技出版物 The Information 报道，经过多年的传闻和猜测，苹果正在推进其首款可折叠 iPhone 的生产。消息人士称，苹果已开始与供应商讨论具体组件要求，并提供了有关可折叠设备以及即将推出的 iPhone 16、iPhone 17 和改进版 iPhone SE 的若干新细节。

### [🌟 乔布斯 1983 年演讲视频曝光](https://osxdaily.com/2024/07/27/watch-steve-jobs-speak-at-the-1983-international-design-conference/)

来源：OS X Daily

发布时间：2024-07-28 00:12:38

史蒂夫·乔布斯档案馆分享了一段时长一小时的视频，展示了 28 岁的乔布斯在 1983 年阿斯彭国际设计大会上的演讲，以及乔尼·艾维的一些想法，以及一些旧照片和苹果产品。

## iOS Blog

### [Flutter初探之渲染管道（二）](https://juejin.cn/post/7395969637877448758)

来源：掘金 iOS

发布时间：2024-07-28 14:06:40

本文深入探讨了 Flutter 渲染管道的第二阶段，重点介绍了 Render Tree 根节点的创建和初始化过程。文章从 runApp 函数开始，逐步梳理了 Widget Tree、Element Tree 和 Render Tree 的构建过程，并分析了 `_RawViewElement.mount` 函数中 `renderObject.prepareInitialFrame();` 行的作用。通过打断点调试，作者展示了 Render Tree 根节点如何被添加到 PipelineOwner 的布局和绘制列表中，为后续的渲染操作做准备。

## Daily Code

### [MinerU：基于 PDF-Extract-Kit 的 PDF 解析工具，支持 PDF 转 Markdown](https://github.com/opendatalab/MinerU)

来源：Trending repositories on GitHub today · GitHub

发布时间：2024-07-29 03:23:58

MinerU 是一款一站式、开源、高质量的数据提取工具，主要功能包括：Magic-PDF（PDF 文档提取）和 Magic-Doc（网页和电子书提取）。

### [🌟 UTM：在 iOS 和 macOS 上运行 Windows、Linux 和更多内容](https://github.com/utmapp/UTM)

来源：Trending Swift repositories on GitHub today · GitHub

发布时间：2024-07-29 05:35:23

UTM 是一款功能齐全的系统模拟器和虚拟机主机，可让你在 Mac、iPhone 和 iPad 上运行 Windows、Linux 等系统。它基于 QEMU，支持 30 多种处理器，包括 x86_64、ARM64 和 RISC-V。UTM 具有 VGA 图形模式、文本终端模式、USB 设备支持和 JIT 加速。对于 macOS，它还支持使用 Hypervisor.framework 和 QEMU 的硬件加速虚拟化，以及使用 Virtualization.framework 在 macOS 12+ 上启动 macOS 访客。
