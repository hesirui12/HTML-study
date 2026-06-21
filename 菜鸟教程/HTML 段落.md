---
title: "HTML 段落"
source: "https://www.w3school.com.cn/html/html_paragraphs.asp"
author:
  - "[[w3school.com.cn]]"
published:
created: 2026-06-18
description: "提供结构清晰、通俗易懂的 Web 开发教程，内含海量实战示例，涵盖 HTML、CSS、JavaScript、SQL、Python、PHP、Bootstrap、Java、XML 等多种技术。"
tags:
  - "clippings"
---
段落总是在新行开始，通常是一段文本。

## HTML 段落

HTML `<p>` 元素定义段落。

段落总是在新行开始，浏览器会自动在段落前后添加一些空白（边距）。

### 实例

```html
<p>这是一个段落。</p>
<p>这是另一个段落。</p>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_paragraphs_1)

## HTML 显示

您无法确定 HTML 将如何显示。

大屏幕或小屏幕，以及调整窗口大小都会产生不同的结果。

在 HTML 中，您无法通过添加额外的空格或空行来更改显示效果。

浏览器在显示页面时会自动移除任何额外的空格和空行：

### 实例

```html
<p>
This paragraph
contains a lot of lines
in the source code,
but the browser
ignores it.
</p>

<p>
This paragraph
contains         a lot of spaces
in the source         code,
but the        browser
ignores it.
</p>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_paragraphs_2)

## HTML 水平线

`<hr>` 标签在 HTML 页面中定义主题分隔，通常显示为水平线。

`<hr>` 元素用于分隔 HTML 页面中的内容（或定义变化）：

### 实例

```html
<h1>这是标题 1</h1>
<p>这是一些文本。</p>
<hr>
<h2>这是标题 2</h2>
<p>这是其他一些文本。</p>
<hr>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_hr)

`<hr>` 标签是一个空标签，这意味着它没有结束标签。

## HTML 换行

HTML `<br>` 元素定义换行。

如果您想要换行（新行）而不开始新段落，请使用 `<br>` ：

### 实例

```html
<p>这是一个<br>带换行的<br>段落。</p>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_paragraphs_3)

`<br>` 标签是一个空标签，这意味着它没有结束标签。

## 诗歌问题

这首诗将显示为单行：

### 实例

```html
<p>
  春眠不觉晓，
  处处闻啼鸟。
  夜来风雨声，
  花落知多少。
</p>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_poem)

## 解决方案 - HTML <pre> 元素

HTML `<pre>` 元素定义预格式化文本。

`<pre>` 元素内的文本以等宽字体（通常是 Courier）显示，并且保留空格和换行：

### 实例

```html
<pre>
  春眠不觉晓，
  处处闻啼鸟。
  夜来风雨声，
  花落知多少。
</pre>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_pre)

## HTML 标签参考

W3School 的标签参考包含有关 HTML 元素及其属性的更多信息。

| 标签 | 描述 |
| --- | --- |
| [<p>](https://www.w3school.com.cn/tags/tag_p.asp "HTML <p> 标签") | 定义段落。 |
| [<hr>](https://www.w3school.com.cn/tags/tag_hr.asp "HTML <hr> 标签") | 定义内容中的主题变化。 |
| [<br>](https://www.w3school.com.cn/tags/tag_br.asp "HTML <br> 标签") | 插入单个换行。 |
| [<pre>](https://www.w3school.com.cn/tags/tag_pre.asp "HTML <pre> 标签") | 定义预格式化文本。 |

如需查看所有可用 HTML 标签的完整列表，请访问我们的 [HTML 标签参考](https://www.w3school.com.cn/tags/index.asp "HTML 标签参考手册") 。