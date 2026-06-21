---
title: "HTML 注释"
source: "https://www.w3school.com.cn/html/html_comments.asp"
author:
  - "[[w3school.com.cn]]"
published:
created: 2026-06-18
description: "提供结构清晰、通俗易懂的 Web 开发教程，内含海量实战示例，涵盖 HTML、CSS、JavaScript、SQL、Python、PHP、Bootstrap、Java、XML 等多种技术。"
tags:
  - "clippings"
---
HTML 注释不会在浏览器中显示，但它们可以帮助你为 HTML 源代码添加说明文档。

## HTML 注释标签

你可以使用以下语法向 HTML 源代码添加注释：

```html
<!-- 在这里写下你的注释 -->
```

注意：开始标签中有一个感叹号（`!`），但结束标签中没有。

注意：注释不会被浏览器显示，但它们可以帮助你为 HTML 源代码添加说明文档。

## 添加注释

通过注释，你可以在 HTML 代码中放置通知和提醒：

### 实例

```html
<!-- 这是一个注释 -->

<p>这是一个段落。</p>

<!-- 记得在这里添加更多信息 -->
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_comment)

## 隐藏内容

注释可用于隐藏内容。

如果你需要暂时隐藏内容，这会很有帮助：

### 实例

```html
<p>这是一个段落。</p>

<!-- <p>这是另一个段落</p> -->

<p>这也是一个段落。</p>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_comment_hide_1)

你也可以隐藏多行内容。在 `<!--` 和 `-->` 之间的所有内容都会被隐藏，不会显示。

### 实例

隐藏一段 HTML 代码：

```html
<p>这是一个段落。</p>
<!--
<p>看看这张很棒的图片：</p>
<img border="0" src="trulli.jpg" alt="Trulli">
-->
<p>这也是一个段落。</p>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_comment_hide_2)

注释对于调试 HTML 也非常有用，因为你可以一次注释掉一行 HTML 代码，以查找错误。

## 隐藏行内内容

注释可用于隐藏 HTML 代码中间的部分内容。

### 实例

隐藏段落中的一部分：

```html
<p>这<!-- 很棒的文字 -->是一个段落。</p>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_comment_inline)