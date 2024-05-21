---
title: Home page
layout: base
pageClass: home
tags:
-home
-welcome
-info
---
<h2 class="mainHeading">Main Content</h2>
<a href="/toys">Go to toys</a>

<!DOCTYPE html>
<!-- Created By CodingNepal - www.codingnepalweb.com -->
<html lang="en" dir="ltr">
  <head>
    <meta charset="UTF-8">
   <title> Responsive Drop Down Navigation Menu | CodingLab </title>
    <link rel="stylesheet" href="style.css">
    <!-- Boxicons CDN Link -->
    <link href='https://unpkg.com/boxicons@2.0.7/css/boxicons.min.css' rel='stylesheet'>
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
   </head>
<body>
  <nav>
    <div class="navbar">
      <i class='bx bx-menu'></i>
      <div class="logo"><a href="#">Nav</a></div>
      <div class="nav-links">
        <div class="sidebar-logo">
          <span class="logo-name">nab</span>
          <i class='bx bx-x' ></i>
        </div>
        <ul class="links">
          <li><a href="#">HOME</a></li>
          <li>
            <a href="#">Family </a>
            <i class='bx bxs-chevron-down htmlcss-arrow arrow  '></i>
            <ul class="htmlCss-sub-menu sub-menu">
              
              <li class="more">
                <span><a href="#">Family1</a>
                <i class='bx bxs-chevron-right arrow more-arrow'></i>
              </span>
                <ul class="more-sub-menu sub-menu">
                  <li><a href="#">Section</a></li>
                  <li><a href="#">Section</a></li>
                  <li><a href="#">Section</a></li>
                   <li><a href="#">Section</a></li>
                </ul>
              </li>
              <li class="more">
                <span><a href="#">Family2</a>
                <i class='bx bxs-chevron-right arrow more-arrow'></i>
              </span>
                <ul class="more-sub-menu sub-menu">
                  <li><a href="#">Section</a></li>
                  <li><a href="#">Section</a></li>
                  <li><a href="#">Section</a></li>
                   <li><a href="#">Section</a></li>
                </ul>
              </li>
              <li class="more">
                <span><a href="#">Family3</a>
                <i class='bx bxs-chevron-right arrow more-arrow'></i>
              </span>
                <ul class="more-sub-menu sub-menu">
                  <li><a href="#">Section</a></li>
                  <li><a href="#">Section</a></li>
                  <li><a href="#">Section</a></li>
                   <li><a href="#">Section</a></li>
                </ul>
              </li>
              <li class="more">
                <span><a href="#">Family4</a>
                <i class='bx bxs-chevron-right arrow more-arrow'></i>
              </span>
                <ul class="more-sub-menu sub-menu">
                  <li><a href="#">Section</a></li>
                  <li><a href="#">Section</a></li>
                  <li><a href="#">Section</a></li>
                 <li><a href="#">Section</a></li>
                </ul>
              </li>
            </ul>
            
        
          <li><a href="#">ABOUT US</a></li>

        </ul>
      </div>
      <div class="search-box">
        <i class='bx bx-search'></i>
        <div class="input-box">
          <input type="text" placeholder="Search...">
        </div>
      </div>
    </div>
  </nav>
  <script src="script.js"></script>
</body>
</html>


## Other instructions

You can write in either markdown OR HTML and can even mix them both together on the same page

Later you will also see that you can put nunjucks code in these files too.

You will create a .md file here for each .html file you would have made in a normal siet.

Don't forget the front matter!
