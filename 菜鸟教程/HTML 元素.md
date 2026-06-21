---
title: "HTML 元素"
source: "https://www.w3school.com.cn/html/html_elements.asp"
author:
  - "[[w3school.com.cn]]"
published:
created: 2026-06-18
description: "提供结构清晰、通俗易懂的 Web 开发教程，内含海量实战示例，涵盖 HTML、CSS、JavaScript、SQL、Python、PHP、Bootstrap、Java、XML 等多种技术。"
tags:
  - "clippings"
---
HTML 元素由开始标签、内容和结束标签定义。

## HTML 元素

HTML *元素* 是从开始标签到结束标签的所有内容：

```html
<tagname>内容放在这里...</tagname>
```

一些 HTML 元素的例子：

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

## 嵌套的 HTML 元素

HTML 元素可以嵌套（这意味着元素可以包含其他元素）。

所有 HTML 文档都由嵌套的 HTML 元素组成。

下面的例子包含四个 HTML 元素（ `<html>` 、 `<body>` 、 `<h1>` 和 `<p>` ）：

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

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_elements)

### 实例解析

`<html>` 元素是根元素，它定义了整个 HTML 文档。

它有一个开始标签 `<html>` 和一个结束标签 `</html>` 。

然后，在 `<html>` 元素内部有一个 `<body>` 元素：

```html
<body>

<h1>我的第一个标题</h1>
<p>我的第一个段落。</p>

</body>
```

`<body>` 元素定义了文档的主体。

它有一个开始标签 `<body>` 和一个结束标签 `</body>` 。

然后，在 `<body>` 元素内部还有另外两个元素： `<h1>` 和 `<p>` ：

```html
<h1>我的第一个标题</h1>
<p>我的第一个段落。</p>
```

<h1> 元素定义了一个标题。

它有一个开始标签 `<h1>` 和一个结束标签 `</h1>` ：

```html
<h1>我的第一个标题</h1>
```

`<p>` 元素定义了一个段落。

它有一个开始标签 `<p>` 和一个结束标签 `</p>` ：

```html
<p>我的第一个段落。</p>
```

## 切勿省略结束标签

即使你忘记结束标签，某些 HTML 元素仍会正确显示：

### 实例

```html
<html>
<body>

<p>这是一个段落。
<p>这是一个段落。

</body>
</html>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_elements_no_endtag)

**但是，永远不要依赖这一点！如果忘记结束标签，可能会出现意外结果和错误！**

## 空的 HTML 元素

没有内容的 HTML 元素称为空元素。

`<br>` 标签定义换行，它是一个没有结束标签的空元素：

### 实例

```html
<p>这是一个带<br>换行的段落。</p>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_elements_br)

## HTML 不区分大小写

HTML 标签不区分大小写： `<P>` 和 `<p>` 含义相同。

HTML 标准不要求使用小写标签，但 W3C *建议* 在 HTML 中使用小写，并且对于更严格的文档类型（如 XHTML） *要求* 使用小写。

在 W3School，我们始终使用小写标签名称。

## HTML 标签参考

W3School 的标签参考包含有关这些标签及其属性的更多信息。

| 标签 | 描述 |
| --- | --- |
| [<html>](https://www.w3school.com.cn/tags/tag_html.asp "HTML <html> 标签") | 定义 HTML 文档的根。 |
| [<body>](https://www.w3school.com.cn/tags/tag_body.asp "HTML <body> 标签") | 定义文档的主体。 |
| [<h1> - <h6>](https://www.w3school.com.cn/tags/tag_hn.asp "HTML <h1> - <h6> 标签") | 定义 HTML 标题。 |

如需查看所有可用 HTML 标签的完整列表，请访问我们的 [HTML 标签参考](https://www.w3school.com.cn/tags/index.asp "HTML 标签参考手册") 。