---
title: Cabañal
date: 2020-07-11 14:43:00 +02:00
layout: page
categories:
- Cabañal
---

  <div class="w3-container w3-third">
  
<h2>Bars</h2>

<ul>
{% assign cabanal_bars = site.bars | where: "categories", "Cabañal" %}
{% for bars in cabanal_bars %}
<li><a href="{{ bars.url }}"> {{ bars.title }}</a></li>
{% endfor %}
</ul>

  </div>
  <div class="w3-container w3-third">
  
  <h2>Cafes</h2>

<ul>
{% assign cabanal_cafes = site.cafes | where: "categories", "Cabañal" %}
{% for cafes in cabanal_cafes %}
<li><a href="{{ cafes.url }}"> {{ cafes.title }}</a></li>
{% endfor %}
</ul>
  
  </div>
  <div class="w3-container w3-third">
  
  <h2>Restaurants</h2>

<ul>
{% assign cabanal_restaurants = site.restaurants | where: "categories", "Cabañal" %}
{% for restaurants in cabanal_restaurants %}
<li><a href="{{ restaurants.url }}"> {{ restaurants.title }}</a></li>
{% endfor %}
</ul>
  
  </div>