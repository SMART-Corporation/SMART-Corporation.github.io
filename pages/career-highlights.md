---
layout: page
title: "Career Highlights"
permalink: /career-highlights
date: 2022-06-12 01:00:00 -0400
categories: career highlights
---

<link rel="stylesheet" type="text/css" href="/assets/css/bootstrap.min.css">

<div id="carouselControls" class="carousel slide w-75 mx-auto" data-ride="carousel">
  <div class="carousel-inner">
    {% for image in site.data.career-highlights %}
    <div class="carousel-item {% if forloop.first %}active{% endif %}">
      <img class="d-block w-100" src="{{ image.path }}" alt="{{ page.title }}">
    </div>
    {% endfor %}
  </div>
  <a class="carousel-control-prev" href="#carouselControls" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselControls" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </a>
</div>

<hr>

<a href="/assets/pdf/Zaki_Alam_Resume.pdf"><img src="/assets/images/download_pdf.svg" width="20px"> Download Zaki Alam Resume (PDF)</a><br>
<a href="/assets/pdf/Zaki_Alam-Career_Highlights.pdf"><img src="/assets/images/download_pdf.svg" width="20px"> Download Zaki Alam - Career Highlights (PDF)</a>
