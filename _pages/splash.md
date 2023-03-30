---
title: "Hi!"
layout: splash
#permalink: /_oldhome
date: 2023-03-30T11:48:41+03:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: 
  actions:
    - label: "More about me"
      url: "/"
excerpt: "My name is **`Chris Weyland`** and I’m an outdoor, cycling and web enthusiast from Germany."
intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
feature_row:
  - image_path: assets/images/header-norway.jpg
    alt: "Norwegian landscape"
    title: "Every journey ends sometimes"
    excerpt: "After almost 5 years of bicycle touring, I'm settling down back home in Europe"
  - image_path: assets/images/header-norway.jpg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: assets/images/header-norway.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: assets/images/header-norway.jpg
    alt: "Norwegian landscape"
    title: "Every journey ends sometimes"
    excerpt: "After almost 5 years of bicycle touring, I'm settling down back home in Europe"
    url: "blog/end-of-a-world-trip"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row2" type="left" %}
