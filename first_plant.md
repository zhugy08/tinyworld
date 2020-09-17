---
layout: page
title: First Plant
---

{% for first_plant in site.first_plant %}
  <h2>第{{ first_plant.day }}天</h2>
  <p>{{ first_plant.content | markdownify }}</p>
{% endfor %}