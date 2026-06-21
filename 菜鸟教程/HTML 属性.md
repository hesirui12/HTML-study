---
title: "HTML 属性"
source: "https://www.w3school.com.cn/html/html_attributes.asp"
author:
  - "[[w3school.com.cn]]"
published:
created: 2026-06-18
description: "提供结构清晰、通俗易懂的 Web 开发教程，内含海量实战示例，涵盖 HTML、CSS、JavaScript、SQL、Python、PHP、Bootstrap、Java、XML 等多种技术。"
tags:
  - "clippings"
---
HTML 属性为 HTML 元素提供附加信息。

## HTML 属性

- 所有 HTML 元素都可以拥有 *属性*
- 属性为元素提供 *附加信息*
- 属性总是在 *开始标签* 中指定
- 属性通常以名称/值对的形式出现，如： **name* =" *value* "*

## href 属性

`<a>` 标签定义超链接。 `href` 属性指定链接目标页面的 URL：

### 实例

```html
<a href="https://www.w3school.com.cn">访问 W3School</a>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_attributes_link)

您将在 [HTML 链接](https://www.w3school.com.cn/html/html_links.asp "HTML 链接") 章节中了解更多关于链接的内容。

## src 属性

`<img>` 标签用于在 HTML 页面中嵌入图像。 `src` 属性指定要显示的图像的路径：

### 实例

```html
<img src="girl.jpg">
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_attributes_img_src)

在 `src` 属性中指定 URL 有两种方式：

*绝对 URL* - 链接到托管在另一个网站上的外部图像。示例：src="https://www.w3school.com.cn/images/girl.jpg"。

注意：外部图像可能受版权保护。如果您未经许可使用，可能违反版权法。此外，您无法控制外部图像；它可能突然被删除或更改。

*相对 URL* - 链接到托管在网站内的图像。此处的 URL 不包含域名。如果 URL 不以斜杠开头，它将相对于当前页面。示例：src="girl.jpg"。如果 URL 以斜杠开头，它将相对于域。示例：src="/images/girl.jpg"。

提示：几乎总是最好使用相对 URL。如果您更改域名，它们不会失效。

## width 和 height 属性

`<img>` 标签还应包含 `width` 和 `height` 属性，它们指定图像的宽度和高度（以像素为单位）：

### 实例

```html
<img src="girl.jpg" width="500" height="600">
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_attributes_img)

## alt 属性

`<img>` 标签必需的 `alt` 属性为图像指定替代文本，以便在图像因某些原因无法显示时使用。这可能由于连接缓慢、 `src` 属性错误或用户使用屏幕阅读器造成。

### 实例

```html
<img src="girl.jpg" alt="戴帽子的女孩">
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_attributes_alt)

### 实例

看看如果我们尝试显示不存在的图像会发生什么：

```html
<img src="typo.jpg" alt="戴帽子的女孩">
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_attributes_alt_error)

您将在 [HTML 图像](https://www.w3school.com.cn/html/html_images.asp "HTML 图像") 章节中了解更多关于图像的内容。

## style 属性

`style` 属性用于为元素添加样式，例如颜色、字体、大小等。

### 实例

```html
<p style="color:red;">这是一个红色段落。</p>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_attributes_style)

您将在 [HTML 样式](https://www.w3school.com.cn/html/html_styles.asp "HTML 样式") 章节中了解更多关于样式的内容。

## lang 属性

您应始终在 `<html>` 标签中包含 `lang` 属性，以声明网页的语言。这旨在帮助搜索引擎和浏览器。

下面的例子指定英语为语言：

```html
<!DOCTYPE html>
<html lang="en">
<body>
...
</body>
</html>
```

国家代码也可以添加到 `lang` 属性的语言代码中。因此，前两个字符定义 HTML 页面的语言，后两个字符定义国家/地区。

下面的例子指定英语为语言，美国为国家/地区：

```html
<!DOCTYPE html>
<html lang="en-US">
<body>
...
</body>
</html>
```

您可以在我们的 [HTML 语言代码参考](https://www.w3school.com.cn/tags/html_ref_language_codes.asp "HTML 语言代码参考手册") 中查看所有语言代码。

## title 属性

`title` 属性定义有关元素的一些额外信息。

当您将鼠标悬停在元素上时， `title` 属性的值将作为工具提示显示：

### 实例

```html
<p title="我是一个工具提示">这是一个段落。</p>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_attributes_title)

## 我们建议：始终使用小写属性

HTML 标准不要求属性名称为小写。

`title` 属性（及所有其他属性）可以大写或小写书写，如 `title` 或 `TITLE` 。

但是，W3C *建议* 在 HTML 中使用小写属性，并且对于更严格的文档类型（如 XHTML） *要求* 使用小写属性。

在 W3School，我们始终使用小写属性名称。

## 我们建议：始终为属性值加引号

HTML 标准不要求属性值加引号。

然而，W3C *建议* 在 HTML 中加引号，并且对于更严格的文档类型（如 XHTML） *要求* 加引号。

### 好：

```html
<a href="https://www.w3school.com.cn/html/">访问我们的 HTML 教程</a>
```

### 不好：

```html
<a href=https://www.w3school.com.cn/html/>访问我们的 HTML 教程</a>
```

有时您必须使用引号。此示例无法正确显示 `title` 属性，因为它包含空格：

### 实例

```html
<p title=Description of W3School>
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_attributes_error)

在 W3School，我们始终为属性值加引号。

## 单引号还是双引号？

在 HTML 中，双引号用于属性值最为常见，但也可以使用单引号。

在某些情况下，当属性值本身包含双引号时，有必要使用单引号：

```html
<p title='Bill "ShotGun" Nelson'>
```

反之亦然：

```html
<p title="Bill 'ShotGun' Nelson">
```

[亲自试一试](https://www.w3school.com.cn/tiy/t.asp?f=html_attributes_single_double)

## 本章总结

- 所有 HTML 元素都可以拥有 *属性*
- `<a>` 的 `href` 属性指定链接目标页面的 URL
- `<img>` 的 `src` 属性指定要显示的图像的路径
- `<img>` 的 `width` 和 `height` 属性提供图像的尺寸信息
- `<img>` 的 `alt` 属性为图像提供替代文本
- `style` 属性用于为元素添加样式，例如颜色、字体、大小等
- `<html>` 标签的 `lang` 属性声明网页的语言
- `title` 属性定义有关元素的一些额外信息

## HTML 属性参考

每个 HTML 元素的所有属性的完整列表，请参阅我们的： [HTML 属性参考](https://www.w3school.com.cn/tags/html_ref_attributes.asp "HTML 属性参考手册") 。