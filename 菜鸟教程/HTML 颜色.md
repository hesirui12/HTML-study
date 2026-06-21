---
title: "HTML 颜色"
source: "https://www.w3school.com.cn/html/html_colors.asp"
author:
  - "[[w3school.com.cn]]"
published:
created: 2026-06-18
description: "提供结构清晰、通俗易懂的 Web 开发教程，内含海量实战示例，涵盖 HTML、CSS、JavaScript、SQL、Python、PHP、Bootstrap、Java、XML 等多种技术。"
tags:
  - "clippings"
---
HTML 颜色可通过预定义的颜色名称，或使用 RGB、HEX、HSL、RGBA 或 HSLA 值来指定。

## 颜色名称

在 HTML 中，可以使用颜色名称来指定颜色：

Tomato

Orange

DodgerBlue

MediumSeaGreen

Gray

SlateBlue

Violet

LightGray

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_color_names)

HTML 支持 [140 种标准颜色名称](https://www.w3school.com.cn/tags/html_ref_colornames.asp "HTML 颜色名") 。

## 背景颜色

你可以为 HTML 元素设置背景颜色：

Welcome to China

China is a great country!

### 实例

```html
<h1 style="background-color:DodgerBlue;">Hello World</h1>
<p style="background-color:Tomato;">Lorem ipsum...</p>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_color_background)

## 文本颜色

你可以设置文本的颜色：

### China

China is a great country!

China, officially the People's Republic of China, is a country in East Asia.

### 实例

```html
<h1 style="color:Tomato;">Hello World</h1>
<p style="color:DodgerBlue;">Lorem ipsum...</p>
<p style="color:MediumSeaGreen;">Ut wisi enim...</p>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_color_text)

## 边框颜色

你可以设置边框的颜色：

Hello World

Hello World

Hello World

### 实例

```html
<h1 style="border:2px solid Tomato;">Hello World</h1>
<h1 style="border:2px solid DodgerBlue;">Hello World</h1>
<h1 style="border:2px solid Violet;">Hello World</h1>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_color_border)

## 颜色值

在 HTML 中，也可以使用 RGB 值、HEX 值、HSL 值、RGBA 值和 HSLA 值来指定颜色。

以下三个 `<div>` 元素使用 RGB、HEX 和 HSL 值设置背景颜色：

rgb(255, 99, 71)

#ff6347

hsl(9, 100%, 64%)

以下两个 `<div>` 元素使用 RGBA 和 HSLA 值设置背景颜色，它们为颜色添加了 Alpha 通道（此处为 50% 透明度）：

rgba(255, 99, 71, 0.5)

hsla(9, 100%, 64%, 0.5)

### 实例

```html
<h1 style="background-color:rgb(255, 99, 71);">...</h1>
<h1 style="background-color:#ff6347;">...</h1>
<h1 style="background-color:hsl(9, 100%, 64%);">...</h1>

<h1 style="background-color:rgba(255, 99, 71, 0.5);">...</h1>
<h1 style="background-color:hsla(9, 100%, 64%, 0.5);">...</h1>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_color_values)

## 了解更多颜色值知识

你将在后续章节中了解更多关于 [RGB](https://www.w3school.com.cn/html/html_colors_rgb.asp "HTML RGB 与 RGBA 颜色") 、 [HEX](https://www.w3school.com.cn/html/html_colors_hex.asp "HTML HEX 颜色") 和 [HSL](https://www.w3school.com.cn/html/html_colors_hsl.asp "HTML HSL 与 HSLA 颜色") 的知识。