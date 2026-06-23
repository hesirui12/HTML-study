---
title: "What Are IDs and Classes, and When Should You Use Them?"
source: "https://www.freecodecamp.org/learn/responsive-web-design-v9/lecture-html-fundamentals/what-are-ids-and-classes"
author:
published:
created: 2026-06-23
description: "Learn to Code — For Free"
tags:
  - "HTML"
---
The `id` attribute adds a unique identifier to an HTML element.  
`id` 属性为 HTML 元素添加了唯一的标识符。

Here is an example of an `h1` element with an `id` of `title`.  
以下是一个包含 `title` 个 `id` 的 `h1` 元素的示例。

Below the `h1` element, add an `h2` element with an `id` set to `"subtitle"`. You can write whatever text you like for the `h2` and you will see the changes in the preview window. To interact with the example, you will need to enable the interactive editor.  
在 `h1` 元素下方，添加一个 `h2` 元素，将其 `id` 属性设置为 `"subtitle"` 。你可以为 `h2` 输入任意文本，然后在预览窗口中查看更改效果。若要与该示例进行交互，需先启用交互式编辑器。

```html
<h1 id="title">Movie Review Page</h1>
```

You can reference the `id` name of `title` within your JavaScript or CSS. Here's a CSS example referencing the `id` of `title` to change the text `color` to `red`.  
你可以在 JavaScript 或 CSS 中引用 `title` 的 `id` 名称。以下是一个 CSS 示例：通过引用 `title` 的 `id` ，将文本 `color` 更改为 `red` 。

**NOTE**: Some CSS has been provided for you in this interactive example. Don't worry about trying to understand the CSS code because you will learn more about that in future lessons. But if you want to see the text color change to blue, enable the interactive editor, click on the `styles.css` tab and change the `color: red;` to `color: blue;`.  
注意：在这个交互式示例中，已经为你准备了一些 CSS 代码。不必试图去理解这些 CSS 代码，因为你将在以后的课程中进一步学习相关知识。不过，如果你想让文本颜色变为蓝色，可以启用交互式编辑器，点击 `styles.css` 标签页，然后将 `color: red;` 的值改为 `color: blue;` 即可。

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta
       name="viewport"
       content="width=device-width, initial-scale=1.0" />
    <title>Review page Example</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>
  <body>
    <h1 id="title">Movie Review Page</h1>
  </body>
</html>
```

```
#title {
  color: red;
}
```

The hash symbol (`#`) in front of `title`, tells the computer you want to target an `id` with that value. `id` names should not be used more than once, and they should always be unique. Another thing to note about `id` values, is that they cannot have spaces in them. Here is an example of applying the words `main` and `heading` to an `id` attribute value:  
在 `title` 前面的井号符号( `#` )告诉计算机：你希望用该值来标识 `id` 。 `id` 的名称不能重复使用，必须保持唯一性。另外， `id` 的值中不能包含空格。以下是一个将 `main` 和 `heading` 应用于 `id` 属性值的示例：

```html
<h1 id="main heading">Main heading</h1>
```

Browsers will see this space as part of the `id` which will lead to unwanted issues when it comes to styling and scripting. `id` attribute values should only contain letters, digits, underscores, and dashes.  
浏览器会将这个区域视为 `id` 的一部分。这样一来，在进行样式设置和脚本编写时，就会遇到各种问题。 `id` 属性的值应仅包含字母、数字、下划线和连字符。

In contrast to the `id` attribute, the `class` attribute value does not need to be unique and can contain spaces.  
与 `id` 属性不同， `class` 属性的值不必唯一，而且可以包含空格。

Here is an example of applying a class called `box` to a `div` element.  
以下是将名为 `box` 的类应用于 `div` 元素的示例。

```html
<div class="box"></div>
```

If you wanted to add multiple class names to an element, you can do so by separating the names by a space. Here is an updated example applying multiple classes to a `div` element.  
如果你想为一个元素添加多个类名，可以用空格将各个类名分隔开来。以下是一个将多个类名应用于 `div` 元素的示例。

```html
<div class="box red-box"></div>
```

Here is another example of applying multiple classes to multiple `div` elements.  
这是将多个类别应用于多个 `div` 元素的另一个示例。

**NOTE**: Some CSS has been provided for you in this interactive example. Don't worry about trying to understand the CSS code because you will learn more about that in future lessons. But if you wanted to change the color of the first and third boxes, enable the interactive editor and click on the `styles.css` tab and change the `background-color: red;` to `background-color: black;`.  
注意：在这个交互式示例中，已经为你准备了一些 CSS 代码。不必试图去理解这些 CSS 代码，因为你将在以后的课程中进一步学习相关知识。不过，如果你想更改第一个和第三个方框的颜色，可以启用交互式编辑器，点击 `styles.css` 标签页，然后将 `background-color: red;` 的值改为 `background-color: black;` 即可。

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta
       name="viewport"
       content="width=device-width, initial-scale=1.0" />
    <title>Colored boxes example</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>
  <body>
    <div class="box red-box"></div>
    <div class="box blue-box"></div>
    <div class="box red-box"></div>
    <div class="box blue-box"></div>
  </body>
</html>
```

```
.box {
  width: 100px;
  height: 100px;
}

.red-box {
  background-color: red;
}

.blue-box {
  background-color: blue;
}
```

So, to recap, when should you use an `id` versus a `class`? Classes are best used when you want to apply a set of styles to many elements. If you want to target a specific element, it is best to use `id` because those values need to be unique.  
那么，总结一下：什么时候应该使用 `id` ，什么时候又该使用 `class` 呢？当您希望为多个元素应用相同的样式时，使用类是最合适的方式。而如果您想针对某个特定的元素进行样式设置，那么最好使用 `id` ，因为该元素的标识符必须是唯一的。