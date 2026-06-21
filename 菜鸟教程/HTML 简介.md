---
title: "HTML 简介"
source: "https://www.w3school.com.cn/html/html_jianjie.asp"
author:
  - "[[w3school.com.cn]]"
published:
created: 2026-06-18
description: "提供结构清晰、通俗易懂的 Web 开发教程，内含海量实战示例，涵盖 HTML、CSS、JavaScript、SQL、Python、PHP、Bootstrap、Java、XML 等多种技术。"
tags:
  - "clippings"
---
HTML 是用于创建网页的标准标记语言。

## 什么是 HTML？

- HTML 指的是超文本标记语言（Hyper Text Markup Language）
- HTML 是创建网页的标准标记语言
- HTML 描述网页的结构
- HTML 由一系列元素组成
- HTML 元素告诉浏览器如何显示内容
- HTML 元素为内容片段添加标签，例如“这是标题”、“这是段落”、“这是链接”等

## 简单的 HTML 文档

### 实例

```html
<!DOCTYPE html>
<html>
<head>
<title>页面标题</title>
</head>
<body>

<h1>我的第一个标题</h1>
<p>我的第一个段落。</p>

</body>
</html>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_intro)

### 例子解释

- `<!DOCTYPE html>` 声明定义此文档为 HTML5 文档
- `<html>` 元素是 HTML 页面的根元素
- `<head>` 元素包含有关 HTML 页面的元信息
- `<title>` 元素为 HTML 页面指定标题（显示在浏览器的标题栏或页面标签页中）
- `<body>` 元素定义文档的主体，是所有可见内容（如标题、段落、图像、超链接、表格、列表等）的容器
- `<h1>` 元素定义大标题
- `<p>` 元素定义段落

## 什么是 HTML 元素？

[[HTML 元素]]由开始标签、内容和结束标签定义：

```html
<tagname> 内容放在这里... </tagname>
```

HTML *元素* 是从开始标签到结束标签的所有内容：

```html
<h1>我的第一个标题</h1>
<p>我的第一个段落。</p>
```

| 开始标签 | 元素内容 | 结束标签 |
| --- | --- | --- |
| `<h1>` | 我的第一个标题 | `</h1>` |
| `<p>` | 我的第一个段落。 | `</p>` |
| `<br>` | 无内容 | 无结束标签 |

注意：有些 HTML 元素没有内容（如 `<br>` 元素）。这些元素称为空元素。空元素没有结束标签！

## 网页浏览器

网页浏览器（如 Chrome、Edge、Firefox、Safari）的用途是读取 HTML 文档并正确显示它们。

浏览器不显示 HTML 标签，而是使用它们来确定如何显示文档：

在浏览器中查看

## HTML 页面结构

以下是 HTML 页面结构的可视化表示：

<html> <head>

<title>页面标题</title>

</head> <body>

<h1>这是一个标题</h1>

<p>这是一个段落。</p>

<p>这是另一个段落。</p>

</body> </html>

注意： `<body>` 部分内的内容将显示在浏览器中。 `<title>` 元素内的内容将显示在浏览器的标题栏或页面的标签页中。

## HTML 历史

自万维网诞生以来，HTML 已经历了许多版本：

| Year | Version |
| --- | --- |
| 1989 | Tim Berners-Lee 发明了万维网 |
| 1991 | Tim Berners-Lee 发明了 HTML |
| 1993 | Dave Raggett 起草了 HTML+ |
| 1995 | HTML 工作组定义了 HTML 2.0 |
| 1997 | W3C 推荐标准：HTML 3.2 |
| 1999 | W3C 推荐标准：HTML 4.01 |
| 2000 | W3C 推荐标准：XHTML 1.0 |
| 2008 | WHATWG HTML5 首个公开草案 |
| 2012 |  |
| 2014 | [W3C 推荐标准：HTML5](http://www.w3.org/TR/html5/) |
| 2016 | W3C 候选推荐标准：HTML 5.1 |
| 2017 | [W3C 推荐标准：HTML5.1 第二版](http://www.w3.org/TR/html51/) |
| 2017 | [W3C 推荐标准：HTML5.2](http://www.w3.org/TR/html52/) |

提示：本教程遵循最新的 HTML5 标准。