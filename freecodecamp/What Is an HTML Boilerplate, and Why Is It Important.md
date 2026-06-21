---
title: "freeCodeCamp.org"
source: "What Is an HTML Boilerplate, and Why Is It Important?"
author:
published:
created: 2026-06-21
description: "Learn to Code — For Free"
tags:
  - "HTML"
---
Let's learn about the HTML boilerplate.  
让我们来了解一下 HTML 模板代码吧。

What is the HTML boilerplate, you ask? It's like a ready-made template for your webpages. Think of it as the foundation of a house. A boilerplate includes the basic structure and essential elements every HTML document needs. It saves you time and helps ensure your pages are set up properly. Here is an example:  
你可能会问，什么是 HTML 模板呢？其实，它就像是为网页准备的现成模板。可以把它想象成房子的基石。HTML 模板包含了每个 HTML 文档都必需的基本结构和要素。使用模板能节省时间，同时确保网页能够正确地被构建出来。以下是一个示例：

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta
       name="viewport"
       content="width=device-width, initial-scale=1.0" />
    <title>freeCodeCamp</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>
  <body>
  </body>
</html>
```

Let's break down the key parts of this boilerplate. First, there is the `DOCTYPE` declaration:  
让我们来分析一下这个模板中的各个关键部分。首先，是 `DOCTYPE` 声明：

```html
<!DOCTYPE html>
```

It tells browsers which version of HTML you're using. Next, comes the `html` tag:  
它告诉浏览器你正在使用的是哪个版本的 HTML。接下来是 `html` 标签：

```html
<!DOCTYPE html>
<html lang="en">
  <!--All other elements go inside here-->
</html>
```

This wraps around all your content, and can specify the language of your page. Inside the `html` tag, you'll find two main sections - a `head`, and a `body`:  
该元素会包裹住页面上的所有内容，同时还可以指定页面的语言。在 `html` 标签中，包含两个主要部分： `head` 和 `body` 。

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <!--Important metadata goes here-->
  </head>
  <body>
    <!--Headings, paragraphs, images, etc. go inside here-->
  </body>
</html>
```

The `head` section contains important behind-the-scenes information:  
`head` 部分包含了重要的幕后信息：

```html
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Document Title Goes Here</title>
  <link rel="stylesheet" href="./styles.css" />
</head>
```

Your site's metadata, contained in `meta` elements, has details about things like character encoding, and how websites like Twitter should preview your page's link. Your site's title, found in the `title` element, determines the text that appears in the browser tab or window. Finally, you'll typically link your page's external stylesheets in the `head` section using `link` elements.  
您网站的元数据包含在 `meta` 元素中，其中包含了有关字符编码等信息，以及像 Twitter 这样的网站应如何预览您页面的链接。您网站的标题则存储在 `title` 元素中，该标题会显示在浏览器的标签页或窗口中。最后，您通常会在 `head` 部分使用 `link` 元素来引用页面的外部样式表。

The `body` section is where all your content goes:  
`body` 部分就是用来存放你所有内容的地方：

```html
<body>
  <h1>I am a main title</h1>
  <p>Example paragraph text</p>
</body>
```

Now, why is a boilerplate important? It ensures your pages are structured correctly and work well across different browsers. Using a boilerplate helps you avoid common mistakes and follow best practices. It's a great starting point for any web project. Remember, you can customize your own boilerplate to fit your needs. As you gain experience, you might add your own preferred elements or `meta` tags. As you continue to improve your personal boilerplate, you'll find that it saves you time when starting new projects.  
那么，为什么模板如此重要呢？它能够确保网页的结构合理，同时保证网页能在各种浏览器上正常显示。使用模板有助于避免常见的错误，同时也能遵循最佳实践。对于任何网页项目来说，模板都是一个很好的起点。请记住，你可以根据自己的需求来定制模板。随着经验的积累，你可以添加自己喜欢的元素或标签。随着你对模板的不断优化，你会发现，它在开始新项目时能为你节省大量时间。

Next time you start a new HTML file, consider using a boilerplate. It will definitely give you a solid foundation to build on.  
下次当你开始创建一个新的 HTML 文件时，不妨使用模板。这肯定会为你后续的工作打下坚实的基础。