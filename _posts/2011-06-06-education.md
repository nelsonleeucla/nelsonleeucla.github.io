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

  {% assign educations = educations | push: "Bachelor of Science in Computer Science|University Name|City, State|September 2020|June 2024|Description of the education experience.|/path/to/your/image1.jpg" %}
  {% assign educations = educations | push: "High School Diploma|High School Name|City, State|September 2016|June 2020|Description of the education experience.|/path/to/your/image2.jpg" %}

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
        <img src="{{ details[6] }}" alt="{{ details[0] }} logo">
      </div>
    </div>
  {% endfor %}
</section>
