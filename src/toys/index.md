---
title: Most Loved Toy 
layout: base
tags: [collection]
---

# {{ title }}
<ul>
  {% for page in collections.toy %}
    <li><a href="{{ page.url }}">{{ page.data.title }}</a></li>
  {% endfor %}
</ul>


  <div class="grid-container">
  {%- for page in collections.toy %}
      <article class="card">
          <a href="{{ page.url }}">
              <img src="/images/{{ page.data.image}}" alt="{{ page.data.imagealt}}" class="card-image">
              <div class="card-info">
                  <h3 class="card-title">{{ page.data.title }}</h3>
                  <p class="card-description">This is a brief description of Toy 1.</p>
              </div>

          </a>
          <div class="card-credit"><a href="{{ page.data.creditlink}}">{{ page.data.credit }}</a></div>
      </article>
      {%- endfor %}
      </div>