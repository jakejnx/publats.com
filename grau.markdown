---
title: Grau
date: 2020-07-11 14:43:00 +02:00
layout: page
---

## Bars2g
  <ul>
{% for bars in bars.categories.Grau %}
<li><a href="{{ bars.url }}"> {{ bars.title }}</a> - {{ bars.categories }} </li>
{% endfor %}
</ul>