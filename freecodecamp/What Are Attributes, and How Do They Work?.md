---
title: What Are Attributes, and How Do They Work?
source: https://www.freecodecamp.org/learn/responsive-web-design-v9/lecture-understanding-html-attributes/what-are-attributes
author:
published:
created: 2026-06-21
description: Learn to Code — For Free
tags:
  - HTML
---


An attribute is a value placed inside the opening tag of an HTML element. Attributes provide additional information about the element or specify how the element should behave. Here is the basic syntax for an attribute:  
属性是指被放置在 HTML 元素的开始标签中的值。属性用于提供有关该元素的额外信息，或指定该元素应如何表现。以下是属性的基本语法：

```html
<element attribute="value"></element>
```

The attribute name is followed by an equal sign (`=`) and a value in quotes. The value can be a string or a number, depending on the attribute.  
属性名称后面跟着等号（ `=` ），再接着是用引号括起来的值。该值可以是字符串，也可以是数字，具体取决于该属性的类型。

This first example uses the `href` and `target` attributes. The `href` attribute specifies the URL of a link and the `target` attribute specifies where to open the link.  
这个例子中使用了 `href` 和 `target` 属性。 `href` 属性用于指定链接的 URL，而 `target` 属性则用于指定打开该链接的地点。

**Note:** The `a` element, also known as the anchor element, is used to create hyperlinks. The text between the opening and closing `a` tags is the clickable part users select to navigate.  
注意： `a` 元素，也被称为锚点元素，用于创建超链接。位于打开标签和关闭标签之间的文本，就是用户可以点击以进行导航的部分。

Enable the interactive editor and change the `href="https://www.freecodecamp.org/news/"` to `href="https://www.freecodecamp.org"`. Now when you click on the link in the interactive editor, you will see the freeCodeCamp homepage in a new browser tab.  
启用交互式编辑器，将 `href="https://www.freecodecamp.org/news/"` 改为 `href="https://www.freecodecamp.org"` 。现在，当您在交互式编辑器中点击该链接时，新浏览器标签页中会显示 freeCodeCamp 的首页。

```html
<a href="https://www.freecodecamp.org/news/" target="_blank">Visit freeCodeCamp</a>
```

Without the `href` attribute, the link would not work because there would be no destination URL. So you must include this `href` attribute to make the link functional. The `target="_blank"` enables the link to open in a new browser tab. You will learn more about the `target` attribute in future lessons.  
如果没有 `href` 属性，该链接将无法正常使用，因为没有目标网址。因此，必须添加 `href` 属性才能使链接生效。 `target="_blank"` 属性则能让链接在新的浏览器标签页中打开。关于 `target` 属性的更多信息，你可以在后续课程中了解。

Other common attributes are the `src`, and `alt`, or alternative, attribute - which is used to specify the source of an image and provide alternative descriptive text for the image, respectively.  
其他常见的属性还有 `src` 和 `alt` 。另外，还有一种替代性属性，用于指定图像的来源，并为该图像提供相应的描述性文字。

Enable the interactive editor and change the `src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg"` to `src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/running-cats.jpg"`. Then change the `alt="Two tabby kittens sleeping together on a couch."` to `alt="Two cats running in the dirt."`.  
启用交互式编辑器，将 `src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg"` 改为 `src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/running-cats.jpg"` 。然后再将 `alt="Two tabby kittens sleeping together on a couch."` 改为 `alt="Two cats running in the dirt."` 。

```html
<img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Two tabby kittens sleeping together on a couch." />
```

Similar to the `href` attribute, the `src` attribute is required because it specifies the image file to be displayed. The `alt` attribute is not required, but it is recommended for accessibility purposes. Accessibility means making sure that everyone, including those with disabilities, can use and understand things like websites, apps, and physical spaces. You will learn more about accessibility in the upcoming lessons.  
与 `href` 属性类似， `src` 属性也是必填的，因为它用于指定要显示的图像文件。 `alt` 属性虽然不是必填的，但为了提升可访问性，建议还是将其设置起来。所谓可访问性，指的是确保包括残疾人在内的所有人都能使用和理解各种网站、应用程序以及各种物理空间。在接下来的课程中，您将了解更多关于可访问性的知识。

Some attributes are a little unique with their syntax like the `checked` attribute.  
有些属性在语法上比较特殊，比如 `checked` 属性。

Enable the interactive editor and try clicking on the checkbox in the preview window to see it alternate between a checked and unchecked state.  
启用交互式编辑器，试着点击预览窗口中的复选框，看看该复选框会在已选中和未选中状态之间切换。

```html
<input type="checkbox" checked />
```

In the following example, we have an `input` element with the `type` attribute set to `checkbox`. Inputs are used to collect data from users, and the `type` attribute specifies the type of input. In this case, this input is a checkbox. You will learn more about how inputs work in the upcoming lessons.  
在下面的例子中，有一个 `input` 元素，其 `type` 属性被设置为 `checkbox` 。输入框用于从用户那里收集数据，而 `type` 属性则用于指定输入的类型。在这个例子中，该输入框属于复选框类型。在接下来的课程中，你将更详细地了解各种输入框的用法。

The `checked` attribute is used to specify that the checkbox should be checked by default. The `checked` attribute does not require a value. If it is present, the checkbox will be checked by default. If the attribute is not present, the checkbox will be unchecked. This is known as a boolean attribute. You will learn more about booleans in general when you get to the JavaScript section.  
`checked` 属性用于指定复选框应处于选中状态。 `checked` 属性不需要赋值。如果该属性存在，复选框将默认处于选中状态；如果该属性不存在，复选框则处于未选中状态。这种属性被称为布尔属性。关于布尔值的更多信息，你可以在学习 JavaScript 时了解到。

Enable the interactive editor and try removing the `checked` attribute from the `input`. You will see that the checkbox is no longer checked by default.  
启用交互式编辑器，试着删除 `input` 中的 `checked` 属性。你会发现，该复选框不再处于默认选中状态了。

```html
<input type="checkbox" checked />
```

There are several common boolean attributes you will encounter in HTML, such as `disabled`, `readonly`, and `required`. These attributes are used to specify the state of an element, such as whether it is disabled, read-only, or required.  
在 HTML 中，你会遇到几种常见的布尔属性，比如 `disabled` 、 `readonly` 和 `required` 。这些属性用于指定元素的状态，比如该元素是否被禁用、是否为只读状态，或者是否为必填项。

Here is an example of a text `input` element that is disabled by default. Enable the interactive editor and try clicking on the `input` element in the preview window. Now remove the `disabled` attribute from the `input` element and you will see that the `input` is no longer disabled by default. You should now be able to click on it and type inside the field.  
以下是一个默认处于禁用状态的 `input` 元素的示例。请启用交互式编辑器，然后尝试点击预览窗口中的 `input` 元素。接着，去掉 `input` 元素上的 `disabled` 属性，你会发现 `input` 元素不再处于禁用状态。现在你应该可以点击该元素并在其中输入文字了。

```html
<input type="text" disabled>
```

HTML has many attributes that can be used to customize the behavior and appearance of elements on a webpage. Understanding how to use attributes is essential for creating interactive and accessible web content. Over the next few lessons, you will learn about more HTML attributes and how to use them effectively in your web development projects.  
HTML 拥有许多属性，这些属性可以用来定制网页上各个元素的行为和外观。了解如何使用这些属性对于创建具有交互性且易于使用的网页内容至关重要。在接下来的几节课中，你将学习更多关于 HTML 属性的知识，以及如何在网页开发项目中有效地运用它们。