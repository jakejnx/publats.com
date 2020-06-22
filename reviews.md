---
title: Reviews
permalink: "/reviews/"
layout: page
---

{% for pubs in site.pubs %}
  <h2>
    <a href="{{ pubs.url }}">
      {{ pubs.title }} - {{ pubs.tags }}
    </a>
  </h2>
{% endfor %}
jakey