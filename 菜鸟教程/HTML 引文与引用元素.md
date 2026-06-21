---
title: "HTML 引文与引用元素"
source: "https://www.w3school.com.cn/html/html_quotation_elements.asp"
author:
  - "[[w3school.com.cn]]"
published:
created: 2026-06-18
description: "提供结构清晰、通俗易懂的 Web 开发教程，内含海量实战示例，涵盖 HTML、CSS、JavaScript、SQL、Python、PHP、Bootstrap、Java、XML 等多种技术。"
tags:
  - "clippings"
---
本章我们将介绍 `<blockquote>` 、 `<q>` 、 `<abbr>` 、 `<address>` 、 `<cite>` 和 `<bdo>` 这些 HTML 元素。

## 实例

以下是来自世界自然基金会网站的引文：

> 60 年来，世界自然基金会一直致力于帮助人类与自然和谐共生。作为全球领先的环保组织，世界自然基金会在近 100 个国家开展工作。在各个层面，我们都与世界各地的人们合作，制定并提供创新的解决方案，以保护社区、野生动物及其栖息地。

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_formatting_intro_2)

## 用于长引用的 HTML <blockquote> 元素

HTML `<blockquote>` 元素定义从其他来源引用的部分。

浏览器通常会对 `<blockquote>` 元素进行缩进。

### 实例

```html
<p>以下是来自世界自然基金会网站的引文：</p>
<blockquote cite="http://www.worldwildlife.org/who/index.html">
60 年来，世界自然基金会一直致力于帮助人类与自然和谐共生。作为全球领先的环保组织，世界自然基金会在近 100 个国家开展工作。在各个层面，我们都与世界各地的人们合作，制定并提供创新的解决方案，以保护社区、野生动物及其栖息地。
</blockquote>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_formatting_blockquote)

## 用于短引用的 HTML <q> 元素

HTML `<q>` 标签定义短引用。

浏览器通常会在引用周围添加引号。

### 实例

```html
<p>世界自然基金会的目标是：<q>构建人类与自然和谐共处的未来。</q></p>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_formatting_q)

## 用于缩写的 HTML <abbr> 元素

HTML `<abbr>` 标签定义缩写或首字母缩略词，如 "HTML"、"CSS"、"Mr."、"Dr."、"ASAP"、"ATM"。

标记缩写可以为浏览器、翻译系统和搜索引擎提供有用信息。

提示：请使用全局 `title` 属性，在鼠标悬停在元素上时显示缩写/首字母缩略词的完整描述。

### 实例

```html
<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_formatting_abbr)

## 用于联系信息的 HTML <address> 元素

HTML `<address>` 标签定义文档或文章作者/所有者的联系信息。

联系信息可以是电子邮件地址、URL、物理地址、电话号码、社交媒体账号等。

`<address>` 元素中的文本通常以斜体呈现，浏览器总是在该元素前后添加换行。

### 实例

```html
<address>
作者：Bill Gates。<br>
访问我们：<br>
Example.com<br>
邮箱 564，迪士尼乐园<br>
美国
</address>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_formatting_address)

## 用于作品标题的 HTML <cite> 元素

HTML `<cite>` 标签定义创作作品的标题（如书籍、诗歌、歌曲、电影、绘画、雕塑等）。

注意：人名不是作品标题。

`<cite>` 元素中的文本通常以斜体呈现。

### 实例

```html
<p><cite>呐喊</cite>由爱德华·蒙克创作。绘制于 1893 年。</p>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_formatting_cite)

## 用于双向覆盖的 HTML <bdo> 元素

BDO 代表双向覆盖（Bi-Directional Override）。

HTML `<bdo>` 标签用于覆盖当前文本方向：

### 实例

```html
<bdo dir="rtl">这段文字将从右向左书写</bdo>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_formatting_bdo)

## HTML 引文与引用元素

| 标签 | 描述 |
| --- | --- |
| [<abbr>](https://www.w3school.com.cn/tags/tag_abbr.asp "HTML <abbr> 标签") | 定义缩写或首字母缩略词。 |
| [<address>](https://www.w3school.com.cn/tags/tag_address.asp "HTML <address> 标签") | 定义文档作者/所有者的联系信息。 |
| [<bdo>](https://www.w3school.com.cn/tags/tag_bdo.asp "HTML <bdo> 标签") | 定义文本方向。 |
| [<blockquote>](https://www.w3school.com.cn/tags/tag_blockquote.asp "HTML <blockquote> 标签") | 定义从其他来源引用的部分。 |
| [<cite>](https://www.w3school.com.cn/tags/tag_cite.asp "HTML <cite> 标签") | 定义作品标题。 |
| [<q>](https://www.w3school.com.cn/tags/tag_q.asp "HTML <q> 标签") | 定义短的行内引用。 |

如需查看所有可用 HTML 标签的完整列表，请访问我们的 [HTML 标签参考](https://www.w3school.com.cn/tags/index.asp "HTML 标签参考手册") 。