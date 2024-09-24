---
title: "Daily News #2024-09-24"
date: "2024-09-24 08:41:30"
description: "微软投资挽救苹果
🤯如何让Swift中的日期保持微秒精度"
tags: 
- '微软'
- 'Swift'
- '苹果'

---

> - 微软投资挽救苹果
> - 🤯如何让Swift中的日期保持微秒精度

## Apple News

### [微软投资挽救苹果](https://www.cultofmac.com/news/microsoft-investment-saves-apple)

来源：Hacker News - Newest: "apple"

发布时间：2024-09-23 23:29:40

1997年，微软向苹果投资1.5亿美元，帮助苹果度过了难关。作为交换，苹果同意在Mac上引入微软的Internet Explorer，并保证微软将在未来五年内为Mac提供Office支持。这笔投资对两家公司都有利，微软获得了苹果的非投票权股票，而苹果获得了现金和微软的支持。

## iOS Blog

### [🤯如何让Swift中的日期保持微秒精度](https://augmentedcode.io/2024/09/23/how-to-keep-dates-microseconds-precision-in-swift/)

来源：Blog – Augmented Code

发布时间：2024-09-23 23:00:00

DateFormatter用于将日期和时间的字符串表示转换为Date类型，反之亦然。需要注意的是，转换会丢失微秒精度。如果我们对这些Date值进行排序，这非常重要，否则最终会导致顺序不正确。让我们考虑一个使用Core Data的iOS应用程序，其中日期用于对实体进行排序。如果我们不保留微秒精度，则排序将不正确，因为两个日期可能在秒上相等，但在微秒上不同。
