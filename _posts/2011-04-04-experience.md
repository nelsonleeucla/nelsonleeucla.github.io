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

  {% assign experiences = experiences | push: "Marketing Team Member|UCLA Radio|Los Angeles, CA|April 2024|Present|• Manage the external brand of radio through digital and in-person marketing campaigns.<br>• Develop creative strategies and content to promote Radio events, programs, and products.<br>• Manage Radio's various social media platforms including Instagram, TikTok, Twitter, and Reddit." %}
  {% assign experiences = experiences | push: "Social Media Marketing Intern|Friends Collection|Remote|January 2024|June 2024|• Develop and execute strategies that optimize the company’s social media marketing funnel.<br>• Utilize Meta Ads Manager to execute the production and management of paid advertisements to drive sales growth.<br>• Perform A/B testing to gain insights on which paid advertising campaigns perform most optimally.<br>• Create compelling and visually appealing content for Instagram, TikTok, Facebook, YouTube shorts, and Reddit.<br>• Assist in content scheduling, posting, and engagement on Instagram, TikTok, Facebook, YouTube shorts, and Reddit.<br>• Monitor social media trends and industry developments to ensure strategies remain current and effective.<br>• Utilize HubSpot CRM for crafting and executing engaging email marketing campaigns." %}
  {% assign experiences = experiences | push: "Beats by Dr. Dre Branding Strategy and Business Analytics Externship|Extern|Remote|April 2024|May 2024|• Conducted consumer trends research, focusing on the audio industry and GenZ behaviors, identifying driving factors.<br>• Executed end-to-end consumer research; from scoping to data analysis and participant engagement.<br>• Developed insights into GenZ audio device preferences and how to capitalize on them." %}
  {% assign experiences = experiences | push: "National Research Group Market Research Externship|Extern|Remote|March 2024|April 2024|• Conducted comprehensive research on the policy influence landscape regarding the environment within the European region, uncovering critical insights to inform strategic decision-making.<br>• Strategically identified and shortlisted the top 8 policy influencers driving significant advancements in the environment and community impact across the European region, based on their contributions and influence.<br>• Executed in-depth secondary research to compile essential data on the identified policy influencers, including contact information, key contributions, and their overall impact, facilitating targeted engagement strategies." %}
  {% assign experiences = experiences | push: "Resident Advisor|UCR Residential Life|Riverside, CA|September 2022|June 2023|• Supported 67 residents in their personal and academic lives throughout their year-long stay in the residential community.<br>• Planned, marketed, and hosted multiple events/programs for residents which required budgeting, creating promotional posters and flyers, advertising successfully, and cooperating with other departments on campus.<br>• Led conflict resolution meetings between residents to resolve any disputes.<br>• Interviewed and assessed future potential resident advisors.<br>• Conducted administrative duties in the community including maintenance requests and incident reports.<br>• Participated in 24-hour period &quot;on-duty&quot; shifts, responding to emergencies and unexpected situations effectively and calmly." %}
  {% assign experiences = experiences | push: "Research Assistant|Adversity and Adaptation Lab|Riverside, CA|June 2022|June 2023|• Led a small team in completing a coding project that analyzed parent-child relationships.<br>• Led data-gathering sessions where participants would attend and complete surveys regarding racial bias." %}
  {% assign experiences = experiences | push: "Research Assistant|BioBehavioral Research Lab|Riverside, CA|June 2022|March 2023|• Utilized ArcGIS and R’Studios software to analyze data regarding food deserts in the United States.<br>• Became familiarized with the process of producing psychological research papers." %}
  {% assign experiences = experiences | push: "Restaurant Server|The Hopyard American Alehouse & Grill|Pleasanton, CA|March 2021|September 2023|• Provided a friendly and welcoming customer service experience to patrons.<br>• Worked effectively in a team environment to ensure the success of the restaurant's operations." %}

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
