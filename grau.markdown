---
title: Grau
date: 2020-07-11 14:43:00 +02:00
---

## Bars
<ul>
{% for bars | where:"category","Grau" in site.bars  %}
<li><a href="{{ bars.url }}"> {{ bars.title }}</a> </li>
{% endfor %}
</ul>