---
title: "What Is the Role of Open Graph Tags, and How Do They Affect SEO?"
source: "https://www.freecodecamp.org/learn/responsive-web-design-v9/lecture-understanding-how-html-affects-seo/what-is-the-role-of-open-graph-tags"
author:
published:
created: 2026-06-23
description: "Learn to Code — For Free"
tags:
  - "HTML"
---
The open graph protocol enables you to control how your website's content appears across various social media platforms, such as Facebook, LinkedIn, and many more. By setting these open graph properties, you can entice users to want to click and engage with your content. You can set these properties through a collection of `meta` elements inside your HTML `head` section.  
开放图谱协议让你能够掌控自己网站的内容在各种社交媒体平台上的呈现方式，比如 Facebook、LinkedIn 等等。通过设置这些开放图谱属性，你可以吸引用户点击并互动你的内容。你可以在 HTML 的部分中，使用相应的标签来设置这些属性。

The first important OG property to include would be the `title`. Here is an example of setting the OG `title` for the freeCodeCamp homepage:  
首先需要设置的重要 OG 属性就是 `title` 。以下是为例，在 freeCodeCamp 的主页上设置 OG `title` 的操作：

Example Code 示例代码
```html
<meta content="freeCodeCamp.org" property="og:title" />
```

For the `property` attribute, you will need to specify that it is `og:title`. The `content` attribute is where you will write the title you want displayed for social media sites.  
对于 `property` 属性，你需要将其指定为 `og:title` 。而 `content` 属性则用于输入你希望在社交媒体上显示的标题。

The next important OG property would be the `type`. Here is an example of using the OG `type` for the freeCodeCamp homepage:  
下一个重要的 OG 属性就是 `type` 。以下是使用 OG `type` 来设计 freeCodeCamp 主页的示例：

Example Code 示例代码
```html
<meta property="og:type" content="website" />
```

The `type` property is used to represent the type of content being shared on social media. Examples of this content include articles, websites, videos, or music.  
`type` 属性用于表示在社交媒体上分享的内容类型。这类内容包括文章、网页、视频或音乐等。

The third important OG property would be the `image`. Here is an example of setting the OG `image` for the freeCodeCamp homepage:  
第三个重要的 OG 属性就是 `image` 。以下是为例，在 freeCodeCamp 的主页上设置 OG `image` 的方法：

Example Code 示例代码
```html
<meta
  content="https://cdn.freecodecamp.org/platform/universal/fcc_meta_1920X1080-indigo.png"
  property="og:image"
/>
```

In this example, the open graph image is pointing to the freeCodeCamp logo. All of these images should be high quality with good dimensions and ratios. Most social media platforms will include criteria for image requirements to help you ensure that your content displays well on their site. For example, the developers.facebook.com documentation page states:  
在这个例子中，所展示的图片实际上指向了 freeCodeCamp 的标志。所有这些图片都应具有高质量、合适的尺寸和比例。大多数社交媒体平台都会对图片格式有相应的要求，这样就能确保你的内容能在他们的平台上正常显示。例如，developers.facebook.com 的文档中就有相关说明：

"use images that are at least 1200 by 630 pixels for the best display on high resolution devices. At the minimum, you should use images that are 600 by 315 pixels to display link page posts with larger images."  
为了在高分辨率设备上获得最佳的显示效果，建议使用至少 1200 像素×630 像素的图片。如果需要显示包含较大尺寸图片的帖子，那么图片的尺寸至少应达到 600 像素×315 像素。

The fourth important OG property would be the `url`. Here is an example of setting the OG `url` for the freeCodeCamp homepage:  
第四个重要的 OG 属性就是 `url` 。以下是为例，在 freeCodeCamp 的主页上设置 OG `url` 的方法：

Example Code 示例代码
```html
<meta property="og:url" content="https://www.freecodecamp.org" />
```

There are many more OG properties that you can set, like `description`, `audio`, `video` and `locale`. However, the open graph `url`, `image`, `type`, and `title` are the most important ones to include.  
你还可以设置许多其他的属性，比如 `description` 、 `audio` 、 `video` 和 `locale` 。不过，其中最重要的还是开放图谱相关的属性 `url` 、 `image` 、 `type` 和 `title` 。

So how do these open graph properties affect Search Engine Optimization? When your content is shared on social media, well-crafted OG properties can enhance the appearance for your content in users' feeds. This can lead to higher click-through rates which could signal to search engines that your content is relevant and engaging.  
那么，这些开放图谱属性究竟如何影响搜索引擎优化呢？当你的内容被分享到社交媒体上时，如果开放图谱属性设置得当，就能提升内容在用户信息流中的展示效果。这样一来，点击率就会上升，而搜索引擎也会因此认为你的内容具有相关性和吸引力。