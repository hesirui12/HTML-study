---
title: "What Is the Role of the Link Element in HTML, and How Can It Be Used to Link to External Stylesheets?"
source: "https://www.freecodecamp.org/learn/responsive-web-design-v9/lecture-understanding-the-html-boilerplate/what-is-the-role-of-the-link-element-in-html"
author:
published:
created: 2026-06-21
description: "Learn to Code — For Free"
tags:
  - "HTML"
---
## What Is the Role of the Link Element in HTML, and How Can It Be Used to Link to External Stylesheets?在 HTML 中，link 元素的用途是什么？如何利用它来链接到外部样式表呢？

Let's learn about the `link` element, and how to use it to link to external stylesheets.  
让我们来了解一下 `link` 元素，以及如何利用它来链接到外部样式表。

The `link` element is used to link to external resources like stylesheets and site icons. Here is the basic syntax for using the `link` element for an external CSS file:  
`link` 元素用于链接到外部资源，比如样式表和网站图标。以下是使用 `link` 元素来链接外部 CSS 文件的基本语法：

```html
<link rel="stylesheet" href="./styles.css" />
```

The `rel` attribute is used to specify the relationship between the linked resource and the HTML document. In this situation, we need to specify that this linked resource is a `stylesheet`.  
`rel` 属性用于指定被链接资源与 HTML 文档之间的关系。在这种情况下，我们需要明确指出，该被链接资源属于 `stylesheet` 类型。

It is considered best practice to separate your HTML and CSS in different files. Developers will use the `link` element for their external CSS file instead of writing everything in the HTML document.  
将 HTML 和 CSS 分别保存在不同的文件中，是一种最佳实践。开发人员会使用 `link` 元素来引用外部 CSS 文件，而不会把所有 CSS 代码都写在 HTML 文档中。

The `href` attribute is used to specify the location of the URL for the external resource.  
`href` 属性用于指定外部资源的 URL 所在位置。

The `dot` followed by a forward slash in the example tells the computer to look in the current folder, or directory, for the `styles.css` file.  
在示例中， `dot` 后面跟着一个正斜杠，这一格式告诉计算机在当前文件夹或目录中查找 `styles.css` 文件。

The `link` element should be placed inside the `head` element as seen in the following example:  
如以下示例所示， `link` 元素应被放置在 `head` 元素的内部。

```html
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Examples of the link element</title>
  <link rel="stylesheet" href="./styles.css" />
</head>
```

Often times you will see multiple `link` elements inside a professional codebase that link to different stylesheets, fonts, and icons. Here is an example of using the `link` element to link to an external Google Font called *Playwright Cuba*:  
在专业的代码库中，你经常会看到多个 `link` 元素，这些元素分别指向不同的样式表、字体和图标。以下是一个使用 `link` 元素来链接到名为 Playwright Cuba 的谷歌字体的例子：

```html
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link
  href="https://fonts.googleapis.com/css2?family=Playwrite+CU:wght@100..400&display=swap"
  rel="stylesheet"
/>
```

Google Fonts are a set of free and open source custom fonts that you can use inside any project. You can choose which fonts you would like to use and Google will provide you with the necessary HTML and CSS code. In this example, the `preconnect` value for the `rel` attribute tells the browser to create an early connection to the value specified in the `href` attribute. This is done to speed up loading times for these external resources.  
Google Fonts 是一组免费且开源的定制字体，您可以在任何项目中使用它们。您可以自行选择想要使用的字体，Google 会提供所需的 HTML 和 CSS 代码。在这个例子中， `rel` 属性中的 `preconnect` 值告诉浏览器提前与 `href` 属性中指定的地址建立连接。这样做是为了缩短这些外部资源的加载时间。

Another common use case for the `link` element is to link to icons. Here is an example of linking to a favicon:  
`link` 元素的另一个常见用途是用于创建指向图标的链接。以下是一个指向网站图标链接的示例：

```html
<link rel="icon" href="favicon.ico" />
```

A favicon, which is short for favorite icon, is a small icon typically displayed in the browser tab next to the site title. A lot of websites will use a favicon to display their brand icon.  
Favicon，即“收藏图标”的简称，是一种小型图标，通常显示在浏览器标签页上，位于网站标题的旁边。许多网站都会使用 Favicon 来展示自己的品牌标识。