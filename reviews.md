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
{% for Cafes in site.Cafes %}
<li><a href="{{ Cafes.url }}"> {{ Cafes.title }}</a> - {{ Cafes.tags }} </li>
{% endfor %}
</ul>
