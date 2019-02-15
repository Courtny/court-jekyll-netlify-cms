---
layout: post
title: Test Post with Markdown
date: 2019-01-30 00:00:00
categories: design
description: This page is a demo that shows everything you can do inside portfolio and blog posts.
featured_image: '/images/demo/demo-square.jpg'
---
![](/images/demo/demo-landscape.jpg)

## Demo content

This page is a demo that shows everything I can do inside portfolio and blog posts.

Include everything I need to create engaging posts about my work, and show off case studies in a beautiful way.

**Obviously,** I’ve styled up *all the basic* text formatting options [available in markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

I can create lists:

* Simple bulleted lists
* Like this one
* Are cool

And:

1. Numbered lists
2. Like this other one
3. Are great too

I can also add blockquotes, which are shown at a larger width to help break up the layout and draw attention to key parts of the content:

> “Simple can be harder than complex: You have to work hard to get your thinking clean to make it simple. But it’s worth it in the end because once you get there, you can move mountains.”

The theme also supports markdown tables:

| Item                 | Author        | Supports tables? | Price |
|----------------------|---------------|------------------|-------|
| This is a test    | Cool Guy | Yes              | $39   |
| Another test   | Bossanova | Yes              | $39   |
| Test 2 | Warrior | Yes              | $39   |

You can throw in some horizontal rules too:

---

### Image galleries

Here's a really neat custom feature – galleries:

<div class="gallery" data-columns="3">
	<img src="/images/demo/demo-portrait.jpg">
	<img src="/images/demo/demo-landscape.jpg">
	<img src="/images/demo/demo-square.jpg">
	<img src="/images/demo/demo-landscape-2.jpg">
</div>

Inspired by the Galleries feature from WordPress, it's easy to create grid layouts for images. Just use a bit of simple HTML in the post to create a masonry grid image layout:

```html
<div class="gallery" data-columns="3">
    <img src="/images/demo/demo-portrait.jpg">
    <img src="/images/demo/demo-landscape.jpg">
    <img src="/images/demo/demo-square.jpg">
    <img src="/images/demo/demo-landscape-2.jpg">
</div>
```

*See what I did there? Code and syntax highlighting is built-in too!*

Change the number inside the 'columns' setting to create different types of gallery for all kinds of purposes. I can even click on each image to seamlessly enlarge it on the page.

---

### Image carousels

Here's another gallery with only one column, which creates a carousel slide-show instead.

A nice little feature: the carousel only advances when it is in view, so visitors won't scroll down to find it half way through your images.

<div class="gallery" data-columns="1">
	<img src="/images/demo/demo-landscape.jpg">
	<img src="/images/demo/demo-landscape-2.jpg">
</div>

### What about videos?

Videos are an awesome way to show off work in a more engaging and personal way, and we’ve made sure they work great on our themes. Just paste an embed code from YouTube or Vimeo, and the theme makes sure it displays perfectly:

<iframe src="https://player.vimeo.com/video/148003889" width="640" height="360" frameborder="0" allowfullscreen></iframe>
