---
title: Reviews
permalink: "/reviews/"
layout: page
---

## Pubs
<ul>
{% for pubs in site.pubs %}
<li><a href="{{ pubs.url }}"> {{ pubs.title }}</a> - {{ pubs.tags }} </li>
{% endfor %}
</ul>

## Cafes
<ul>
{% for pubs in site.cafes %}
<li><a href="{{ cafes.url }}"> {{ cafes.title }}</a> - {{ cafes.tags }} </li>
{% endfor %}
</ul>