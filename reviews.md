---
title: Reviews
permalink: "/reviews/"
layout: page
---

## Bars
<ul>
{% for bars in site.bars %}
<li><a href="{{ bars.url }}"> {{ bars.title }}</a> - {{ bars.tags }} </li>
{% endfor %}
</ul>

## Cafes
<ul>
{% for cafes in site.cafes %}
<li><a href="{{ cafes.url }}"> {{ cafes.title }}</a> - {{ cafes.tags }} </li>
{% endfor %}
</ul>


## Restaurants
<ul>
{% for restaurants in site.restaurants %}
<li><a href="{{ restaurants.url }}"> {{ restaurants.title }}</a> - {{ restaurants.tags }} </li>
{% endfor %}
</ul>
