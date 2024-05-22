---
title: Home Page
layout: base
pageClass: home
tags:
  - home
  - welcome
  - info
---
<h2 class="mainHeading">Main Content</h2>
<a href="/toys">Go to toys</a>
 <div class="carousel-container">
        <div class="carousel-wrapper">
            <div class="carousel-content">
              {%- for post in collections.family %}
                <div class="carousel-item">
                    <div class="carousel-image">
                        <img src="/images/{{post.data.image}}" alt="{{post.data.imagealt}}">
                    </div>
                    <div class="carousel-text">
                        <h1 >{{post.data.title}}</h1>
                       <a href="{{post.url}}" class="read-more-btn">Read More</a>
                    </div>
                </div>
                {%- endfor %}
               </div>
        </div>
       </div>

       <button class="carousel-btn prev" onclick="prevSlide()">&#10094;</button>
       <button class="carousel-btn next" onclick="nextSlide()">&#10095;</button>
   

   ## Toys
  <div class="image-grid">
   {%- for post in collections.family %}
        <div class="image-item">
        <a href="{{post.url}}" class="read-more-btn">
          <img src="/images/{{post.data.toyimage}}" alt="{{post.data.toyimagealt}}">
        </a>
    </div>
  {%- endfor %}
  </div>