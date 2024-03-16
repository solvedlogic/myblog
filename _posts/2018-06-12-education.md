---
layout: post
title: "Education must also train one for quick, resolute and effective thinking."
author: sena
categories: [Lifestyle]
image: assets/images/3.jpg
beforetoc: "Prism highlighter is a very powerful thing. In this article I'm going to show you what you can actually do with it, some tricks and tips while editing your post. Tocs is also enabled as you can see in summary."
toc: true
---

Memoirs theme has Prism highlighter integrated. I will show you in this post a few examples of how it looks if you are a developer planning to add pieces of code on your website.

![Alt text](https://plus.unsplash.com/premium_photo-1664361480105-33afc4559c40?q=80&w=1846&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

#### HTML

```html
<li class="ml-1 mr-1">
  <a target="_blank" href="#">
    <i class="fab fa-twitter"></i>
  </a>
</li>
```

#### CSS

```css
.highlight .c {
  color: #999988;
  font-style: italic;
}
.highlight .err {
  color: #a61717;
  background-color: #e3d2d2;
}
```

#### JS

```js
// alertbar later
$(document).scroll(function () {
  var y = $(this).scrollTop();
  if (y > 280) {
    $(".alertbar").fadeIn();
  } else {
    $(".alertbar").fadeOut();
  }
});
```

#### Python

```python
print("Hello World")
```

#### Ruby

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

#### C

```c
printf("Hello World");
```
