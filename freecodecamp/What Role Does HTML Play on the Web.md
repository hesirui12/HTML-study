---
title: What Role Does HTML Play on the Web
source: https://www.freecodecamp.org/learn/responsive-web-design-v9/lecture-understanding-html-attributes/what-is-html
author:
published:
created: 2026-06-21
description: Learn to Code — For Free
tags:
  - HTML
---
HTML, which stands for Hypertext Markup Language, is a markup language for creating web pages. When you visit a website and see content like paragraphs, headings, links, images, and videos; that's HTML.  
HTML，即超文本标记语言，是一种用于创建网页的标记语言。当你访问某个网站时，所看到的段落、标题、链接、图片和视频等内容，其实都是用 HTML 来呈现的。

Here is a small example using HTML elements. Try editing some of the text in the editor and see the changes update in the preview window.  
以下是一个使用 HTML 元素的小示例。试着在编辑器中修改部分文本，然后查看预览窗口中的变化。

```html
<h1>Main heading element</h1>

<p>I am a paragraph element.</p>
```

HTML represents the content and structure of a webpage through the use of elements. Most elements will have an opening tag and a closing tag. Sometimes those tags are referred to as start and end tags. In between those two tags, you will have the content. This content can be text or other HTML elements.  
HTML 通过各种元素来表示网页的内容和结构。大多数元素都有开始标签和结束标签。有时候，这些标签也被称为起始标签和结束标签。在这两个标签之间，就是网页的内容了。这些内容可以是文本，也可以是其他 HTML 元素。

Here is another example of a paragraph element. Change the text in the editor to say `I love coding!` and see the results in the preview window.  
这是另一个段落元素的示例。请在编辑器中把文本改为 `I love coding!` ，然后查看预览窗口中的效果。

```html
<p>I am a paragraph element.</p>
```

Both opening and closing tags start with a left angle bracket (`<`), and end with a right angle bracket (`>`), with the tag name placed between these angle brackets. While HTML tag names are case-insensitive, it is a widely accepted convention and best practice to write them in lowercase.  
无论是开始标签还是结束标签，都是以左尖括号( `<` )开始，以右尖括号( `>` )结束。标签名称则位于这两个尖括号之间。虽然 HTML 标签名称不区分大小写，但按照通用惯例和最佳实践，建议使用小写字母来书写标签名称。

Here is a closer look at just the opening and closing paragraph tags:  
下面我们来仔细看看开头和结尾的段落标记：

```html
<p>
```

```html
</p>
```

What distinguishes an opening tag from a closing tag is the forward slash (`/`) placed immediately after the left angle bracket in a closing tag. Some HTML elements do not have a closing tag. These are known as void elements.  
开放标签与关闭标签的区别在于：在关闭标签中，左尖括号之后紧接着有一个正斜杠（/）。不过，有些 HTML 元素没有对应的关闭标签。这类元素被称为“空元素”。

Here is an example of an image element which is a void element:  
以下是一个属于“空元素”的图像元素的示例：

```html
<img>
```

Notice that this image element does not have the closing tag and it does not have any content. Void elements cannot have any content and only have a start tag.  
请注意，这个图像元素没有对应的结束标签，而且也不包含任何内容。空元素不允许包含任何内容，只有开始标签而已。

Sometimes you will see void elements that use a `/` before the `>` like this:  
有时，你会看到这样的空元素：在 `>` 之前使用了 `/` 。

```html
<img />
```

While many code formatters like Prettier, will choose to include the `/` in void elements, the HTML spec states that the presence of the `/` "does not mark the start tag as self-closing but instead is unnecessary and has no effect of any kind".  
虽然像 Prettier 这样的代码格式化工具通常会在空元素中包含 `/` ，但根据 HTML 规范， `/` 的存在“并不表示该开始标签是自闭合的”。实际上， `/` 是多余的，没有任何实际作用。

In real world development, you will see both forms so it is important to be familiar with both.  
在现实世界的开发过程中，这两种形式都会出现。因此，熟悉这两种形式非常重要。

If you wanted to display an image, you will need to include a couple of attributes inside your image element. An attribute is a special value used to adjust the behavior for an HTML element.  
如果你想显示一张图片，就需要在图片元素中添加几个属性。所谓属性，其实就是用于调整 HTML 元素行为的特殊数值。

Here is an example of an image element with a `src` attribute. Update the value of the `src` attribute to `"https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg"` and you will see the image change to two cats peacefully sleeping.  
以下是一个带有 `src` 属性的图像元素的示例。将 `src` 属性的值更改为 `"https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg"` ，您就会看到图片中的内容变为两只正在安静睡觉的猫。

```html
<img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/running-cats.jpg" />
```

The `src` attribute is used to specify the location for that image. For image elements, it's good practice to include another attribute called the `alt` attribute. The `alt` attribute is used to provide short, descriptive text for the images.  
`src` 属性用于指定该图像的位置。对于图像元素来说，最好再添加一个名为 `alt` 的属性。 `alt` 属性则用于为图像提供简短的描述性文字。

Here's an example of an image element with the `src` and `alt` attributes. Try breaking the image by updating the `src` value to `"https://.freecodecamp.org/curriculum/cat-photo-app/cats.jpg"`. You will see the image disappear and only the `alt` text show.  
以下是一个带有 `src` 和 `alt` 属性的图像元素的示例。试着将 `src` 的值改为 `"https://.freecodecamp.org/curriculum/cat-photo-app/cats.jpg"` ，看看会发生什么。你会发现图像会消失，只剩下 `alt` 中的文字显示出来。

```html
<img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Two tabby kittens sleeping together on a couch." />
```

So, you might be wondering if HTML by itself is enough to build a website. Well, the answer is: it depends. If you're building a small practice project that only displays text and images, HTML alone might be sufficient. However, if you're creating a modern professional website, you will need to have HTML, CSS, and JavaScript.  
那么，你可能会想知道，仅使用 HTML 是否足以构建一个网站。答案是：视具体情况而定。如果你只是想创建一个仅用于显示文本和图片的小型网站，那么 HTML 可能就足够了。不过，如果你想要打造一个现代化的专业网站，那就必须同时使用 HTML、CSS 和 JavaScript。

HTML is for the content and structure. CSS is for styling. JavaScript is for adding interactivity to your web pages. A good analogy for this is to compare HTML, CSS, and JavaScript with a complete building.  
HTML 负责内容的组织和结构。CSS 则负责页面的样式设计。JavaScript 则用于为网页添加交互功能。可以把 HTML、CSS 和 JavaScript 比作一座完整的建筑物：HTML 是建筑物的框架结构，CSS 是建筑物的外观样式，而 JavaScript 则让建筑物具有各种交互功能。

HTML represents the blocks, concrete, and irons that make up the walls. It's the foundation that makes the building strong. CSS represents the interior and exterior design that makes the house look beautiful. JavaScript represents the electrical and water system that ensures uninterrupted access to water and electricity.  
HTML 相当于构成墙壁的砖块、混凝土等物质。它是让建筑物坚固的基础。CSS 则负责房屋的内部和外部设计，让房子看起来更美观。JavaScript 则相当于负责处理水电系统的部分，确保人们能够持续使用水和电。