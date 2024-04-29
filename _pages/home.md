---
layout: archive
permalink: /
hidden: false
title: " "
#header:
  # overlay_color: "#5e616c"
  # overlay_filter: 0.5
  # overlay_image: /assets/images/header.webp
author_profile: true
classes: wide
feature_row:
  - image_path: /assets/images/image_part_001.webp
    title: "Raison D'être"
    alt: "Raison D'être"
    excerpt: "*Reasons for being*, this is my philosophy, a meaning and purpose. *Memento mori*, time is a limited resource."
    url: "/raison/"
    btn_class: "btn--inverse"
    btn_label: "Reflect"
  - image_path: /assets/images/image_part_002.webp
    title: "Sapere Aude"
    alt: "Sapere Aude"
    excerpt: "*Dare to know*, knowledge is a tool for personal and societal empowerment. This is a knowledge base, powered by Obsidian."
    url: "https://obsidian.thalient.ai/"
    btn_class: "btn--inverse"
    btn_label: "Explore"
  - image_path: /assets/images/image_part_003.webp
    title: "Satori"
    alt: "Satori"
    excerpt: "*Satori* is a sudden, profound enlightenment or awakening. This is a collection of posts that, hopefully, provide insight and realizations."
    url: "/collection/"
    btn_class: "btn--inverse"
    btn_label: "Discover"
---
{% for post in site.posts limit: 5 %}
  {% include archive-single.html %}
{% endfor %}

{% include feature_row id="feature_row" %}
