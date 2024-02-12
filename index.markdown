---
title: "Design Forward"
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/misc/printer.gif
  overlay_size: "0.5"
  #actions:
    #- label: "Download"
    #  url: "https://github.com/mmistakes/minimal-mistakes/"
  #caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "Christopher Rosend │ Undergraduate Mechanical Engineer" <!-- excerpt-end -->
intro: 
  - excerpt: '<p style="font-size:25px;"> Hey! I’m Chris, an Undergraduate at Virginia Tech studying Mechanical Engineering. I’m interested in all things additive manufacturing and would love to enter the field once I graduate. This website details the major things I’ve done throughout college as well as my goals, interests, and anything else I feel like throwing on here. </p> 

  <p><a href="/about/" class="btn btn--primary btn--x-large">About Me ➞</a>' <!-- excerpt-end -->
  #<h1 style="font-size:100px; font-family: monaco"> Works </h1>

feature_row:
  - image_path: assets/images/enable/enable.jpg
    #alt: "e-nable image"
    title: "e-NABLE at Virginia Tech"
    excerpt: "Developing low-cost prosthetics and medical devices for the local community using 3D printing." <!-- excerpt-end -->
    url: /2022/09/16/enable-at-virginia-tech.html
    btn_label: "Read More"
    btn_class: "btn--info"

  - image_path: /assets/images/ldpe-recycling/dreams lab filament.jpg
    #image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    #alt: "LDPE Recycling image"
    title: "LDPE Recycling (DREAMS Lab)"
    excerpt: "Taking low density polyethylene, plastic bags, through the process of filament fabrication while performing strength tests and finding potential applications." <!-- excerpt-end -->
    url: /2023/08/24/ldpe-recycling.html
    btn_label: "Read More"
    btn_class: "btn--info"

  - image_path: /assets/images/vt-cro/vt cro.jpg
    title: "VT CRO - IGVC"
    excerpt: "Senior design project that involves the creation of an autonomous line following robot." <!-- excerpt-end -->
    url: /2023/08/21/vt-cro.html
    btn_label: "Read More"
    btn_class: "btn--info"
  
feature_row2:
  - title: '<p style="font-size:50px; margin: 0px"> Recent Works </p>'


feature_row4:
  - #image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    #alt: "placeholder image 2"
    #title: "Take a look at the rest!"
    excerpt: '<a href="/posts-page/" class="btn btn--primary btn--x-large">Browse all works ➞</a>' <!-- excerpt-end -->
    #url: /posts-page/
    #btn_label: "Browse all works"
    #btn_class: "btn--info"

---

{% include feature_row id="intro" type="justify" %}

{% include feature_row id="feature_row2" type="justify" %}

{% include feature_row %}

{% include feature_row id="feature_row4" type="justify" %}