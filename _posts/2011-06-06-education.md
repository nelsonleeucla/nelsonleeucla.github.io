---
date: 2018-04-21 12:26:40
layout: post
title: Education overview
subtitle: 
description: A detailed look at my education history.
image: https://res.cloudinary.com/dp1pwklel/image/upload/c_fill,w_760,h_399/v1724220560/uclahd_exkfhz.webp
optimized_image: https://res.cloudinary.com/dp1pwklel/image/upload/c_fill,w_380,h_200/v1724220560/uclahd_exkfhz.webp
category: education
tags:
author: 
---

<section class="education-timeline">
  {% assign educations = "" | split: "," %}

  {% capture education1 %}
  Psychology B.A.|University of California, Los Angeles|Los Angeles, CA|September 2023|June 2025|Cumulative 3.89 GPA<br>Transferred from the University of California, Riverside|https://res.cloudinary.com/dp1pwklel/image/upload/v1724906986/uclalogo_wwjriz.png
  {% endcapture %}
  {% assign educations = educations | push: education1 %}
  
  {% capture education2 %}
  Psychology B.A. |University of California, Riverside|Riverside, CA|September 2021|June 2023|Cumulative 3.94 GPA|https://res.cloudinary.com/dp1pwklel/image/upload/v1724906986/uclalogo_wwjriz.png
  {% endcapture %}
  {% assign educations = educations | push: education2 %}

  {% capture education3 %}
  High School Diploma|Foothill Highschool|Pleasanton, CA|September 2017|June 2021|Graduated with a weighted 4.0 GPA|https://res.cloudinary.com/dp1pwklel/image/upload/v1724906986/uclalogo_wwjriz.png
  {% endcapture %}
  {% assign educations = educations | push: education3 %}

  {% for education in educations %}
    {% assign details = education | split: "|" %}
    <div class="education-card">
      <div class="card-content">
        <h2>{{ details[0] }}</h2>
        <h3>{{ details[1] }}</h3>
        <p class="location">{{ details[2] }}</p>
        <p class="date">{{ details[3] }} - {{ details[4] }}</p>
        <p>{{ details[5] }}</p>
      </div>
      <div class="card-image">
        <!-- <p>Debug: Image URL is {{ details[6] }}</p> -->
        <img src="{{ details[6] }}" alt="{{ details[0] }} logo">
      </div>
    </div>
  {% endfor %}
</section>

![Welcome Poster](https://res.cloudinary.com/dp1pwklel/image/upload/v1724632715/appa_fihffc.png)