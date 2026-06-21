---
title: "HTML 基础实例"
source: "https://www.w3school.com.cn/html/html_basic.asp"
author:
  - "[[w3school.com.cn]]"
published:
created: 2026-06-18
description: "提供结构清晰、通俗易懂的 Web 开发教程，内含海量实战示例，涵盖 HTML、CSS、JavaScript、SQL、Python、PHP、Bootstrap、Java、XML 等多种技术。"
tags:
  - "clippings"
---
在本章中，我们将展示一些基础的 HTML 实例。

如果使用了你尚未学到的标签，请不要担心。

## HTML 文档

所有 HTML 文档必须以文档类型声明开头： `<!DOCTYPE html>` 。

HTML 文档本身以 `<html>` 开始，以 `</html>` 结束。

HTML 文档的可见部分位于 `<body>` 和 `</body>` 之间。

### 实例

```html
<!DOCTYPE html>
<html>
<body>

<h1>我的第一个标题</h1>
<p>我的第一个段落。</p>

</body>
</html>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_basic_document)

## <!DOCTYPE> 声明

`<!DOCTYPE>` 声明代表文档类型，帮助浏览器正确显示网页。

它只应出现一次，位于页面顶部（在任何 HTML 标签之前）。

`<!DOCTYPE>` 声明不区分大小写。

HTML5 的 `<!DOCTYPE>` 声明是：

```html
<!DOCTYPE html>
```

## HTML 标题

HTML 标题使用 `<h1>` 到 `<h6>` 标签定义。

`<h1>` 定义最重要的标题。 `<h6>` 定义最不重要的标题：

### 实例

```html
<h1>这是标题 1</h1>
<h2>这是标题 2</h2>
<h3>这是标题 3</h3>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_basic_headings)

## HTML 段落

HTML 段落使用 `<p>` 标签定义：

### 实例

```html
<p>这是一个段落。</p>
<p>这是另一个段落。</p>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_basic_paragraphs)

## HTML 链接

HTML 链接使用 `<a>` 标签定义：

### 实例

```html
<a href="https://www.w3school.com.cn">这是一个链接</a>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_basic_link)

链接的目标在 `href` 属性中指定。

属性用于提供有关 HTML 元素的额外信息。

你将在后续章节中了解更多关于属性的内容。

## HTML 图像

HTML 图像使用 `<img>` 标签定义。

源文件（ `src` ）、替代文本（ `alt` ）、宽度和高度作为属性提供：

### 实例

```html
<img src="w3school.jpg" alt="W3School.com.cn" width="400" height="225">
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_basic_img)

## 如何查看 HTML 源代码

你是否曾经看到一个网页并想知道："嘿！他们是怎么做到的？"

### 查看 HTML 源代码：

在 HTML 页面中按 CTRL + U ，或右键单击页面并选择"查看页面源代码"。这将打开一个新标签页，其中包含页面的 HTML 源代码。

### 检查 HTML 元素：

右键单击一个元素（或空白区域），选择"检查"以查看元素由什么组成（你将同时看到 HTML 和 CSS）。你还可以在打开的元素或样式面板中实时编辑 HTML 或 CSS。