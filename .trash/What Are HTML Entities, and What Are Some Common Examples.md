---
title: "What Are HTML Entities, and What Are Some Common Examples?"
source: "https://www.freecodecamp.org/learn/responsive-web-design-v9/lecture-html-fundamentals/what-are-html-entities"
author:
published:
created: 2026-06-23
description: "Learn to Code — For Free"
tags:
  - "HTML"
---
n HTML entity, or character reference, is a set of characters used to represent a reserved character in HTML.  
HTML 实体或字符引用，是一组用于表示 HTML 中那些被保留下来的特殊字符的字符组合。

Let's say you wanted to display the text `This is an <img/> element` on the screen. If you use the code currently in the editor, it won't display the desired result. Even if you added `src` and `alt` attributes to the example, it would show an image in the middle of the paragraph. Not the desired result. To interact with the example, you will need to enable the interactive editor.  
假设你想在屏幕上显示文本 `This is an <img/> element` 。如果你使用编辑器中现有的代码，将无法得到预期的效果。即使你为该文本添加 `src` 和 `alt` 这些属性，也只会在该段文字的中间显示一幅图片而已。这显然不是我们想要的结果。要想让该示例正常发挥作用，你需要启用交互式编辑器。

```html
<p>This is an <img /> element</p>
```

When the HTML parser sees the less than (`<`) symbol followed by an HTML tag name, it interprets that as an HTML element. That is why you are not getting the desired result of `This is an <img/> element` on the screen.  
当 HTML 解析器看到“小于号( < )”后面跟着一个 HTML 标签名时，它会将其解读为一个 HTML 元素。这就是为什么你在屏幕上无法看到 `This is an <img/> element` 所代表的内容的原因。

To fix this issue, you can use HTML entities. Here is an updated example using the correct HTML entities for the less-than (`<`) and greater-than (`>`) symbols. Now you should see `This is an <img/> element` on the screen.  
要解决这个问题，可以使用 HTML 实体。以下是使用正确的 HTML 实体来表示“小于号”（ `<` ）和“大于号”（ `>` ）的示例。现在，你应该能在屏幕上看到 `This is an <img/> element` 了。

Enable the interactive editor and try adding a `&lt;p&gt;learning is fun&lt;/p&gt;` below the paragraph element. You should see `<p>learning is fun</p>` on the screen.  
启用交互式编辑器，试着在段落元素下方添加一个 `&lt;p&gt;learning is fun&lt;/p&gt;` 。你应该能在屏幕上看到 `<p>learning is fun</p>` 。

```html
<p>This is an &lt;img /&gt; element</p>
```

These types of character references are known as named character references. Named references start with an ampersand sign (`&`) and end with a semicolon (`;`). By using a named character reference, the HTML parser will not confuse this with an actual HTML element.  
这类字符引用被称为“命名字符引用”。命名字符引用以“&”符号开头，以分号结尾。通过使用命名字符引用，HTML 解析器就不会将其误认为是真正的 HTML 元素。

Another type of character reference would be the decimal numeric reference. This character reference starts with an ampersand sign and hash symbol (`#`), followed by one or more decimal digits, followed by a semicolon.  
另一种字符引用方式是十进制数字引用。这种引用以“&”和“#”符号开头，接着是一个或多个十进制数字，最后是一个分号。

Here is an example of using the decimal numeric reference for the less than symbol.  
以下是使用小数数值来表示“小于”符号的示例。

Enable the interactive editor and change the code to see different symbols. You can use `&#169;` for the copyright symbol and `&#174;` for the registered trademark symbol.

```html
&#60;
```

The last type of character reference would be the hexadecimal numeric reference. This character reference starts with an ampersand sign, hash symbol, and the letter `x`. Then it is followed by one or more ASCII hex digits and ends with a semicolon.

Here is an example of using the hexadecimal numeric reference for the less than symbol.

Enable the interactive editor and change the code to see different symbols. You can use `&#x20AC;` for the euro symbol and `&#x03A9;` for the Greek capital letter Omega symbol.

```html
&#x3C;
```