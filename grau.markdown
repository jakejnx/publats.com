---
title: Grau
date: 2020-07-11 14:43:00 +02:00
layout: page
---

## Bars2c
<ul>
{% for bars in bars.categories[grau] %}
<li><a href="{{ bars.url }}"> {{ bars.title }}</a> </li>
{% endfor %}
</ul>