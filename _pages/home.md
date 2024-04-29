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
    title: "Praxis"
    alt: "Praxis"
    excerpt: "*Praxis*, applying theory to practice. These posts aim to bridge the gap between insight and real-world application."
    url: "/collection/"
    btn_class: "btn--inverse"
    btn_label: "Discover"
  - image_path: /assets/images/image_part_002.webp
    title: "Raison D'être"
    alt: "Raison D'être"
    excerpt: "*Reasons for being*, this is my philosophy, my meaning and purpose. This section explores who I am and why I do what I do."
    url: "/raison/"
    btn_class: "btn--inverse"
    btn_label: "Reflect"
  - image_path: /assets/images/image_part_003.webp
    title: "Sapere Aude"
    alt: "Sapere Aude"
    excerpt: "*Dare to know*, knowledge liberates both the individual and enlightens society. These are the tools that I use to deepen understanding."
    url: "https://obsidian.thalient.ai/"
    btn_class: "btn--inverse"
    btn_label: "Explore"

---
<h2>Recent Posts</h2>
{% for post in site.posts limit: 5 %}
  {% include archive-single.html %}
{% endfor %}

{% include feature_row id="feature_row" %}
