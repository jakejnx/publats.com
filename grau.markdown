---
title: Grau
date: 2020-07-11 14:43:00 +02:00
layout: page
---

## Bars2d
{% for category in site.categories %}
  <h2>{{ category[0] }}</h2>
  <ul>
    {% for post in category[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}