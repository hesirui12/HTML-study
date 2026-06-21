---
title: "HTML RGB 与 RGBA 颜色"
source: "https://www.w3school.com.cn/html/html_colors_rgb.asp"
author:
  - "[[w3school.com.cn]]"
published:
created: 2026-06-18
description: "提供结构清晰、通俗易懂的 Web 开发教程，内含海量实战示例，涵盖 HTML、CSS、JavaScript、SQL、Python、PHP、Bootstrap、Java、XML 等多种技术。"
tags:
  - "clippings"
---
RGB 颜色值代表红色、绿色和蓝色光源。
RGBA 颜色值是 RGB 的扩展，增加了 Alpha 通道（透明度）。

## RGB 颜色值

在 HTML 中，颜色可以指定为 RGB 值，使用以下公式：

```
rgb(red, green, blue)
```

每个参数（红色、绿色和蓝色）定义颜色的强度，取值范围为 `0` 到 `255` 。

这意味着有 256 x 256 x 256 = 16777216 种可能的颜色！

例如， `rgb(255, 0, 0)` 显示为红色，因为红色设置为最高值 (`255`)，其他两个（绿色和蓝色）设置为 `0` 。

再例如， `rgb(0, 255, 0)` 显示为绿色，因为绿色设置为最高值 (`255`)，其他两个（红色和蓝色）设置为 `0` 。

要显示黑色，将所有颜色参数设置为 `0` ，像这样： `rgb(0, 0, 0)` 。

要显示白色，将所有颜色参数设置为 `255` ，像这样： `rgb(255, 255, 255)` 。

通过混合下面的 RGB 值进行实验：

rgb(255, 99, 71)

### RED

255

### GREEN

99

### BLUE

71

### 实例

rgb(255, 0, 0)

rgb(0, 0, 255)

rgb(60, 179, 113)

rgb(238, 130, 238)

rgb(255, 165, 0)

rgb(106, 90, 205)

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_color_rgb)

## 灰色阴影

灰色阴影通常使用所有三个参数相等的值来定义：

### 实例

rgb(60, 60, 60)

rgb(100, 100, 100)

rgb(140, 140, 140)

rgb(180, 180, 180)

rgb(200, 200, 200)

rgb(240, 240, 240)

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_color_rgb_gray)

## RGBA 颜色值

RGBA 颜色值是 RGB 颜色值的扩展，增加了 Alpha 通道 - 用于指定颜色的不透明度。

RGBA 颜色值的指定方式为：

```
rgba(red, green, blue, alpha)
```

*alpha* 参数是一个介于 `0.0` （完全透明）和 `1.0` （完全不透明）之间的数字：

通过混合下面的 RGBA 值进行实验：

rgba(255, 99, 71, 0.5)

### RED

255

### GREEN

99

### BLUE

71

### ALPHA

0.5

### 实例

rgba(255, 99, 71, 0)

rgba(255, 99, 71, 0.2)

rgba(255, 99, 71, 0.4)

rgba(255, 99, 71, 0.6)

rgba(255, 99, 71, 0.8)

rgba(255, 99, 71, 1)

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_color_rgba)