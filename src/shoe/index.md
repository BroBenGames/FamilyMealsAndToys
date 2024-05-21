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

<div class="grid-container">
{% for page in collections.shoe %}
        <article class="card">
            <a href="{{ page.url }}">
                <img src=/images/  {{ page.date.image }} alt= " {{ page.data.imagealt }} " class="card-image">
                <div class="card-info">
                    <h3 class="card-title">shoe</h3>
                    <p class="card-description">This is a brief description of shoe.</p>
                </div>
            </a>
        </article>
         {% endfor %}
        </div>