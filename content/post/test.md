---
title: "Test" # Title of the blog post.
date: 2024-02-28T03:37:28+01:00 # Date of post creation.
description: "Article description." # Description used for search engine.
featured: true # Sets if post is a featured post, making appear on the home page side bar.
draft: false # Sets whether to render this page. Draft of true will not be rendered.
toc: true # Controls if a table of contents should be generated for first-level links automatically.
# menu: main
usePageBundles: false # Set to true to group assets like images in the same folder as this post.
featureImage: "/images/building.png" # Sets featured image on blog post.
featureImageAlt: 'building' # Alternative text for featured image.
featureImageCap: 'building.' # Caption (optional).
thumbnail: "/images/building.png" # Sets thumbnail image appearing inside card on homepage.
shareImage: "/images/building.png" # Designate a separate image for social media sharing.
codeMaxLines: 10 # Override global value for how many lines within a code block before auto-collapsing.
codeLineNumbers: false # Override global value for showing of line numbers within code block.
figurePositionShow: true # Override global value for showing the figure label.
categories:
  - category
  - category2
tags:
  - Tag_name1
  - Tag_name2
# comment: true # Disable comment if false.
---

**Insert Lead paragraph here.**

## Link

[Test](http://www.google.com){googletest}

## Images

![texthere](/images/dollar.png "althere").

## simple table

   Name | Age
--------|------
    Bob | 27
  Alice | 23

## YouTube Privacy Enhanced Shortcode

{{< youtube g3tYBjv674c >}}

## Twitter Simple Shortcode

{{< tweet user="SanDiegoZoo" id="1453110110599868418" >}}

## Vimeo Simple Shortcode

{{< vimeo_simple 48912912 >}}

## i need this

<blockquote [Element: blockquote]>

In the above example `content` directory, there are four leaf
bundles:

**about**: This leaf bundle is at the root level (directly under
    `content` directory) and has only the `index.md`.

**my-post**: This leaf bundle has the `index.md`, two other content
    Markdown files and two image files. **image1** is a page resource of `my-post`
    and only available in `my-post/index.md` resources. **image2** is a page resource of `my-post`
    and only available in `my-post/index.md` resources.

**my-other-post**: This leaf bundle has only the `index.md`.

**another-leaf-bundle**: This leaf bundle is nested under couple of
    directories. This bundle also has only the `index.md`.

_The hierarchy depth at which a leaf bundle is created does not matter,
as long as it is not inside another **leaf** bundle._
</blockquote>
