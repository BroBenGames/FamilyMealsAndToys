---
title: Family jewelry
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
        <article class="card">
            <a href="toy1.html">
                <img src="https://source.unsplash.com/500x500/?toy" alt="Toy 1" class="card-image">
                <div class="card-info">
                    <h3 class="card-title">Toy 1</h3>
                    <p class="card-description">This is a brief description of Toy 1.</p>
                </div>
            </a>
        </article>
        </div>