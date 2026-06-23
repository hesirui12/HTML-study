---
title: "What are Div Elements and When Should You Use Them?"
source: "https://www.freecodecamp.org/learn/responsive-web-design-v9/lecture-html-fundamentals/what-are-div-elements"
author:
published:
created: 2026-06-23
description: "Learn to Code — For Free"
tags:
  - "HTML"
---
The `div` element is used as a container to group other elements.  
`div` 元素被用作容器，用于将其他元素组合在一起。

Here is an example of a `div` element. Add another paragraph element inside of the `div` element and see the changes in the preview window. To see the previews, you will need to enable the interactive editor.  
以下是一个 `div` 元素的示例。请在 `div` 元素内部再添加一个段落元素，然后查看预览窗口中的变化。要查看预览效果，需要启用交互式编辑器。

```html
<div>
  <p>Example paragraph element.</p>
</div>
```

You will mainly use the `div` element when you want to group HTML elements that will share a set of CSS styles. You will learn more about CSS in future lessons and workshops.  
当你想要将那些需要应用相同 CSS 样式的 HTML 元素组合在一起时，主要就需要使用 `div` 元素。关于 CSS 的更多内容，你可以在后续的课程和培训中学习到。

Even though the `div` element is commonly used in real world codebases, you should be careful not to overuse it. There are times when another element would be more appropriate.  
虽然 `div` 元素在现实世界的代码中很常见，但使用时仍需谨慎，避免过度使用。在某些情况下，使用其他元素可能更为合适。

For example, if you wanted to divide up your content into sections, then the `section` element would be more appropriate than a `div` element.  
例如，如果你想将内容分成几个部分来展示，那么使用 `section` 元素会比使用 `div` 元素更合适。

Add another `section` element below the first one. Then inside of the `section` element, add an `h2` and a `p` element. You can use whatever text you like and you will see the changes in the preview window. To interact with the example, you will need to enable the interactive editor.  
在第一个 `section` 元素下方再添加一个 `section` 元素。然后在 `section` 元素内部，分别添加一个 `h2` 元素和一个 `p` 元素。你可以使用任何你想用的文本，更改后会立即显示在预览窗口中。若要与该示例进行交互，需先启用交互式编辑器。

```html
<section>
  <h2>Mammals</h2>
  <p>
    Mammals are warm-blooded animals with fur or hair. Most give birth to live
    young.
  </p>
  <ul>
    <li>Lion</li>
    <li>Elephant</li>
    <li>Dolphin</li>
  </ul>
</section>
```

The `section` element has semantic meaning over the `div` element which is not semantic. Semantics are the meaning of words or phrases in a language. In HTML, which is a language, elements have their own semantic meaning too. So, this means if you use a `section` element, the browser will pick up its semantic meaning and understand to treat this as a section - on desktops, mobiles, you name it.  
`section` 元素具有语义意义，而 `div` 元素则没有语义意义。所谓“语义”，指的是语言中单词或短语的含义。作为一种语言，HTML 中的各个元素也都有各自的语义含义。因此，如果你使用 `section` 元素，浏览器会理解其语义含义，从而将其视为一个独立的区域——无论是在桌面端还是移动端上。