---
layout: career_highlights
title: "Career Highlight"
date: 2022-06-12 01:00:00 -0400
categories: career highlights
excerpt_separator: <!--post-contents-->
---

<!--post-contents-->
<link rel="stylesheet" href="/assets/css/bootstrap.min.css">

<div id="carouselControls" class="carousel slide w-75 mx-auto" data-ride="carousel">
  <div class="carousel-inner">
    {% for image in site.data.career_highlights %}
    <div class="carousel-item {% if forloop.first %}active{% endif %}">
      <img class="d-block w-100" src="{{ image.path }}" alt="{{ page.title }}">
    </div>
    {% endfor %}
  </div>
  <a class="carousel-control-prev" href="#carouselControls" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselControls" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>