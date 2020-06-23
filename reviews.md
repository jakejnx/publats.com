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
{% for Cafés in site.Cafés %}
<li><a href="{{ Cafés.url }}"> {{ Cafés.title }}</a> - {{ Cafés.tags }} </li>
{% endfor %}
</ul>