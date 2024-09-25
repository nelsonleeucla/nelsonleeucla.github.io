---
date: 2024-08-15 23:57:59
layout: post
title: Previous Experiences
subtitle: 
description: An overview of past positions and extracurricular activities.
image: https://res.cloudinary.com/dp1pwklel/image/upload/v1724305710/radio_msluhq.png
optimized_image: https://res.cloudinary.com/dp1pwklel/image/upload/c_fill,w_380,h_200/v1724305710/radio_msluhq.png
category: experience
tags:
author: 
---

<section class="experience-timeline">
  {% assign experiences = "" | split: "," %}

  {% assign experiences = experiences | push: "Esports Marketing Coordinator|UCLA Recreation|Los Angeles, CA|September 2024|Present|• Develop marketing plans and strategies for Esports and Gaming events and campaigns, including sponsor integrations, pre-event and live event promotions, partner and event announcements, giveaway campaigns, and alumni engagement. <br>• Manage UCLA Esports and Gaming social media on Twitter, Instagram, TikTok, Discord, YouTube, and Twitch.<br>• Assisting in maintaining and utilizing the Esports and Gaming email marketing list and its alumni subset. <br>• Compiling post-event marketing analytics and reports for both sponsor review and internal review.<br>• Produce marketing videos, including concept development, filming, and editing." %}
  {% assign experiences = experiences | push: "Marketing Team Member|UCLA Radio|Los Angeles, CA|April 2024|Present|• Manage the external brand of radio through digital and in-person marketing campaigns.<br>• Develop creative strategies and content to promote Radio events, programs, and products.<br>• Manage Radio's various social media platforms including Instagram, TikTok, Twitter, and Reddit." %}
  {% assign experiences = experiences | push: "Social Media Marketing Intern|Friends Collection|Remote|January 2024|June 2024|• Managed and created engaging content for Instagram, TikTok, Facebook, YouTube shorts, and Reddit.<br>• Organized and executed paid advertising campaigns using Meta Ads Manager to drive sales growth.<br>• Performed A/B testing to gain insights on which paid advertising campaigns perform most optimally.<br>• Utilize HubSpot CRM for crafting and executing engaging email marketing campaigns.<br>• Monitor social media trends and industry developments to ensure strategies remain current and effective." %}
  {% assign experiences = experiences | push: "Beats by Dr. Dre Branding Strategy and Business Analytics Externship|Extern|Remote|April 2024|May 2024|• Conducted consumer trends research, focusing on the audio industry and GenZ behaviors, identifying driving factors.<br>• Executed end-to-end consumer research; from scoping to data analysis and participant engagement.<br>• Developed insights into GenZ audio device preferences and how to capitalize on them." %}
  {% assign experiences = experiences | push: "National Research Group Market Research Externship|Extern|Remote|March 2024|April 2024|• Strategically identified the top policy influencers driving significant environmental advancements across the European region.<br>• Executed in-depth secondary research to compile essential data on the identified policy influencers." %}
  {% assign experiences = experiences | push: "Resident Advisor|UCR Residential Life|Riverside, CA|September 2022|June 2023|• Supported 67 residents in their personal and academic lives throughout their year-long stay in the residential community.<br>• Organized and hosted resident events, managing budgeting, marketing, and collaboration with campus departments.<br>• Led conflict resolution meetings between residents to resolve any disputes.<br>• Responded to and resolved emergencies within the community while working 24-hour shifts as the resident advisor on duty.<br>• Conducted administrative duties in the community including maintenance requests and incident reports.<br>• Interviewed and assessed future potential resident advisors.<br>• Awarded the ‘Future Resident Director/Assistant Director Award’ for exemplary performance as a resident advisor and potential for a successful career in Residential Life." %}
  {% assign experiences = experiences | push: "Research Assistant|Adversity and Adaptation Lab|Riverside, CA|June 2022|June 2023|• Led a small team in completing a coding project that analyzed parent-child relationships.<br>• Led research sessions where participants completed tasks as part of studies on racial bias." %}
  {% assign experiences = experiences | push: "Research Assistant|BioBehavioral Research Lab|Riverside, CA|June 2022|March 2023|• Utilized ArcGIS and R’Studios software to analyze data regarding food deserts in the United States.<br>• Became familiarized with the process of producing psychological research papers." %}
  {% assign experiences = experiences | push: "Restaurant Server|The Hopyard Alehouse & Grill|Pleasanton, CA|March 2021|September 2023|• Provided a warm and welcoming atmosphere for patrons, ensuring personalized service by remembering regular customers’ preferences and addressing their needs promptly.<br>• Possessed in-depth knowledge of the menu and successfully upsold items to increase sales and customer satisfaction.<br>• Resolved customer complaints in a professional manner through effective communication and problem-solving skills.<br>• Managed multiple tables and large parties during busy shifts without compromising service quality." %}

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
