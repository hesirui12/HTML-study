---
title: "What Is the Role of the Script Element in HTML, and How Can It Be Used to Link to External JavaScript Files?"
source: "https://www.freecodecamp.org/learn/responsive-web-design-v9/lecture-html-fundamentals/what-is-the-role-of-the-script-element-in-html"
author:
published:
created: 2026-06-23
description: "Learn to Code — For Free"
tags:
  - "HTML"
---
The `script` element is used to embed executable code. Most developers will use this to execute JavaScript code. JavaScript is used to add interactivity to your web pages. Common examples of using JavaScript include interactive games, image sliders, and dynamic forms that validate user input in real-time.  
`script` 元素用于嵌入可执行代码。大多数开发者会用它来执行 JavaScript 代码。JavaScript 的作用是为网页增添交互性。使用 JavaScript 的常见场景包括制作互动游戏、图片滑块，以及能够实时验证用户输入的动态表单。

Here is an example of using the `script` element in an HTML document. Remove the `//` from in front of the `alert("Welcome to freeCodeCamp");` and you should see an alert pop up. To see the previews, you will need to enable the interactive editor.  
以下是在 HTML 文档中使用 `script` 元素的示例。请去掉 `alert("Welcome to freeCodeCamp");` 前面的 `//` ，这样应该会弹出警告框。如需查看预览效果，需启用交互式编辑器。

```html
<body>
  <script>
    // alert("Welcome to freeCodeCamp");
  </script>
</body>
```

While you can technically write all of your JavaScript code inside the `script` tags, it is considered best practice to link to an external JavaScript file instead. Here is an example of using the `script` element to link to an external JavaScript file:  
虽然从技术上来说，你可以把所有的 JavaScript 代码都写在 `script` 标签里，但最佳做法是链接到外部的 JavaScript 文件。以下是使用 `script` 元素来链接到外部 JavaScript 文件的示例：

```html
<script src="path-to-javascript-file.js"></script>
```

The `src` attribute is used here to specify the location for that external JavaScript file. `src` stands for "source". The reason why it is not encouraged to place all of your JavaScript inside the HTML document is because of separation of concerns. Separation of concerns is a design principle where you separate your programs into distinct sections and have each section address a separate concern. In this case, we want to separate our JavaScript code from our HTML code.  
在这里， `src` 属性用于指定该外部 JavaScript 文件的位置。 `src` 代表“源代码”。不建议将所有的 JavaScript 代码都放在 HTML 文档中，这是因为需要遵循“职责分离”的设计原则。所谓“职责分离”，就是将程序拆分成不同的部分，让每个部分只负责处理特定的任务。在这种情况下，我们希望将 JavaScript 代码与 HTML 代码分开处理。