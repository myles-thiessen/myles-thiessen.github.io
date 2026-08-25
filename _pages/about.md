---
layout: about
title: about
permalink: /
subtitle:

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info:
#  more_info: >
#    <p>mthiessen [at] cs [dot] toronto [dot] edu</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false 
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a PhD student in the Department of Computer Science at the University of Toronto, advised by Professor Eyal de Lara and Professor Sam Toueg. My research interests are in the theory and practice of distributed computing.

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>

