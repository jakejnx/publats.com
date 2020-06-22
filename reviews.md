---
title: Reviews
permalink: "/reviews/"
layout: page
---

{% for pubs in site.pubs %}
  * <a href="{{ pubs.url }}"> {{ pubs.title }} - {{ pubs.tags }}    </a>

{% endfor %}