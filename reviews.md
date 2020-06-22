---
title: Reviews
permalink: "/reviews/"
layout: page
---

{% for pubs in site.pubs %}
  <h2>
    <a href="{{ pubs.url }}">
      {{ pub.name }} - {{ pub.category }}
    </a>
  </h2>
{% endfor %}


[jekyll-organization]: https://github.com/jekyll