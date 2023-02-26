---
layout: page
title: 🏢 Anbieter
---

{% for vendor in site.vendors %}
  <h2><a href="{{ vendor.url }}">{{ vendor.title }}</a></h2>
{% endfor %}
