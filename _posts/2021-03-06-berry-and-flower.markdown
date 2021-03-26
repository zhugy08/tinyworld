---
layout: post
title: 草莓和牵牛花
date: 2021-03-06 08:00 +0800
categories: plant
show_excerpts: true
---

爸爸买来了草莓和牵牛花的种植套装，种种看希望这次能够成功。

{% for second_plant in site.second_plant %}
  <h2>{{ second_plant.day }}</h2>
  <p>{{ second_plant.content | markdownify }}</p>
{% endfor %}
