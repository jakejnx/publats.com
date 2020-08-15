---
title: Grau
date: 2020-07-11 14:43:00 +02:00
layout: page
categories:
- Grau
---

  <div class="w3-container w3-third">
  
<h2>Bars</h2>

<ul>
{% assign grau_bars = site.bars | where: "categories", "Grau" %}
{% for bars in grau_bars %}
<li><a href="{{ bars.url }}"> {{ bars.title }}</a></li>
{% endfor %}
</ul>

  </div>
  <div class="w3-container w3-third">
  
  <h2>Cafes</h2>

<ul>
{% assign grau_cafes = site.cafes | where: "categories", "Grau" %}
{% for cafes in grau_cafes %}
<li><a href="{{ cafes.url }}"> {{ cafes.title }}</a></li>
{% endfor %}
</ul>
  
  </div>
  <div class="w3-container w3-third">
  
  <h2>Restaurants</h2>

<ul>
{% assign grau_restaurants = site.restaurants | where: "categories", "Grau" %}
{% for restaurants in grau_restaurants %}
<li><a href="{{ restaurants.url }}"> {{ restaurants.title }}</a></li>
{% endfor %}
</ul>
  
  </div>