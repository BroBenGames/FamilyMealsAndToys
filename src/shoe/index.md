---
title: Family shoes
layout: base
tags: [collection]
---

# {{ title }}

<ul>
  {% for page in collections.shoe %}
    <li><a href="{{ page.url }}">{{ page.data.title }}</a></li>
  {% endfor %}
</ul>