---
date: 2018-10-09 12:26:40
layout: post
title: Previous experiences
subtitle: 
description: Overview of past positions and extracurricular activities.
image: https://res.cloudinary.com/dp1pwklel/image/upload/v1724305710/radio_msluhq.png
optimized_image: https://res.cloudinary.com/dp1pwklel/image/upload/c_fill,w_380,h_200/v1724305710/radio_msluhq.png
category: experience
tags:
author: 
---

<section class="experience-timeline">
  {% assign experiences = "" | split: "," %}
  {% assign experiences = experiences | push: "Senior Developer|Tech Company A|City, Country|July 2023|Present|Led a team of developers in creating a scalable web application." %}
  {% assign experiences = experiences | push: "Mid-Level Developer|Tech Company B|City, Country|May 2021|June 2023|Developed several key features for an e-commerce platform." %}
  {% assign experiences = experiences | push: "Junior Developer|Tech Company C|City, Country|March 2019|April 2021|Worked on bug fixes and small feature enhancements." %}

  {% for experience in experiences %}
    {% assign details = experience | split: "|" %}
    <div class="experience-card {% cycle 'left', 'right' %}">
      <div class="card-content">
        <h2>{{ details[0] }}</h2>
        <h3>{{ details[1] }}</h3>
        <p class="location">{{ details[2] }}</p>
        <p class="date">{{ details[3] }} - {{ details[4] }}</p>
        <p>{{ details[5] }}</p>
      </div>
    </div>
  {% endfor %}
</section>