---
layout: page
title: "Career Highlight"
permalink: /career_highlights
date: 2022-06-12 01:00:00 -0400
categories: career highlights
---

<link rel="stylesheet" type="text/css" href="/assets/css/bootstrap.min.css">

<div id="carouselIndicators" class="carousel slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#carouselIndicators" data-slide-to="0" class="active"></li>
    <li data-target="#carouselIndicators" data-slide-to="1"></li>
    <li data-target="#carouselIndicators" data-slide-to="2"></li>
    <li data-target="#carouselIndicators" data-slide-to="3"></li>
    <li data-target="#carouselIndicators" data-slide-to="4"></li>
    <li data-target="#carouselIndicators" data-slide-to="5"></li>
    <li data-target="#carouselIndicators" data-slide-to="6"></li>
    <li data-target="#carouselIndicators" data-slide-to="7"></li>
    <li data-target="#carouselIndicators" data-slide-to="8"></li>
  </ol>
  <div class="carousel-inner">
    {% for image in site.data.career_highlights %}
    <div class="carousel-item {% if forloop.first %}active{% endif %}">
      <img class="d-block w-100" src="{{ image.path }}" alt="{{ page.title }}">
    </div>
    {% endfor %}
  </div>
  <a class="carousel-control-prev" href="#carouselIndicators" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselIndicators" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
