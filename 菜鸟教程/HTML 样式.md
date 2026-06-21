---
title: "HTML 样式"
source: "https://www.w3school.com.cn/html/html_styles.asp"
author:
  - "[[w3school.com.cn]]"
published:
created: 2026-06-18
description: "提供结构清晰、通俗易懂的 Web 开发教程，内含海量实战示例，涵盖 HTML、CSS、JavaScript、SQL、Python、PHP、Bootstrap、Java、XML 等多种技术。"
tags:
  - "clippings"
---
HTML `style` 属性用于为元素添加样式，例如颜色、字体、大小等。

## 实例

```html
我是红色

我是蓝色

我是大号字
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_styles_intro)

## HTML Style 属性

设置 HTML 元素的样式可以通过 `style` 属性实现。

HTML `style` 属性的语法如下：

```html
<tagname style="属性:值;">
```

*属性* 是 CSS 属性。 *值* 是 CSS 值。

您将在本教程后续内容中了解更多关于 CSS 的知识。

## 背景颜色

CSS `background-color` 属性定义 HTML 元素的背景颜色。

### 实例

将页面背景颜色设置为浅蓝色：

```html
<body style="background-color:powderblue;">

<h1>这是一个标题</h1>
<p>这是一个段落。</p>

</body>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_styles_background-color_1)

### 实例

为两个不同元素设置背景颜色：

```html
<body>

<h1 style="background-color:powderblue;">这是一个标题</h1>
<p style="background-color:tomato;">这是一个段落。</p>

</body>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_styles_background-color_2)

## 文本颜色

CSS `color` 属性定义 HTML 元素的文本颜色：

### 实例

```html
<h1 style="color:blue;">这是一个标题</h1>
<p style="color:red;">这是一个段落。</p>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_styles_color)

## 字体

CSS `font-family` 属性定义 HTML 元素使用的字体：

### 实例

```html
<h1 style="font-family:verdana;">这是一个标题</h1>
<p style="font-family:courier;">这是一个段落。</p>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_styles_font-family)

## 文本大小

CSS `font-size` 属性定义 HTML 元素的文本大小：

### 实例

```html
<h1 style="font-size:300%;">这是一个标题</h1>
<p style="font-size:160%;">这是一个段落。</p>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_styles_font-size)

## 文本对齐

CSS `text-align` 属性定义 HTML 元素的水平文本对齐方式：

### 实例

```html
<h1 style="text-align:center;">居中对齐的标题</h1>
<p style="text-align:center;">居中对齐的段落。</p>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_styles_text-align)

## 本章总结

- 使用 `style` 属性为 HTML 元素添加样式
- 使用 `background-color` 设置背景颜色
- 使用 `color` 设置文本颜色
- 使用 `font-family` 设置文本字体
- 使用 `font-size` 设置文本大小
- 使用 `text-align` 设置文本对齐