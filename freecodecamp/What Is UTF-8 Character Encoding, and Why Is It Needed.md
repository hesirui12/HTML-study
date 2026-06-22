---
title: "What Is UTF-8 Character Encoding, and Why Is It Needed?"
source: "https://www.freecodecamp.org/learn/responsive-web-design-v9/lecture-understanding-the-html-boilerplate/what-is-utf-8-character-encoding"
author:
published:
created: 2026-06-22
description: "Learn to Code — For Free"
tags:
  - "HTML"
---
UTF-8, or UCS Transformation Format 8, is a standardized character encoding widely used on the web. Character encoding is the method computers use to store characters as data. Essentially, all text on a web page is a sequence of characters stored as one or more bytes. In computing, a byte is a unit of data consisting of 8 bits, or binary digits. UTF-8 supports every character in the Unicode character set - and this includes characters and symbols from all writing systems, languages, and technical symbols. Here is an example of using the `meta` element with the `charset` attribute to set the character encoding to `UTF-8`:  
UTF-8，即 UCS 转换格式 8，是一种在网络上广泛使用的标准化字符编码方式。字符编码是计算机用来将字符以数据形式存储的方法。实际上，网页上的所有文本都是由多个字节构成的字符序列。在计算机领域，一个字节由 8 位二进制数字组成。UTF-8 能够支持 Unicode 字符集中的所有字符——这包括各种文字系统、语言中的字符以及各种技术符号。以下是一个示例：使用 `meta` 元素和 `charset` 属性来将字符编码设置为 `UTF-8` ：

```html
<meta charset="UTF-8" />
```

By setting the character encoding to UTF-8, it will ensure that the accented `"e"` character (`é`) is displayed correctly on the page. Here is an extended code example of using the UTF-8 character encoding:  
将字符编码设置为 UTF-8 后，就能确保带重音符号的 `"e"` 字符（即 `é` ）能在页面上正确显示。以下是使用 UTF-8 字符编码的示例代码：

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Examples of the UTF-8 encoding</title>
  </head>
  <body>
    <p>Café</p>
  </body>
</html>
```

For each new project you create, you should include this `meta` element with the `charset` attribute set to `UTF-8`.  
对于你创建的每一个新项目，都应包含这个 `meta` 元素，同时将 `charset` 属性设置为 `UTF-8` 。