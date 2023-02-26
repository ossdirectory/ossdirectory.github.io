---
layout: page
title: COMMUNITIES 👥
---
{% for community in site.communities %}
  <h2><a href="{{ community.url }}">{{ community.title }}</a></h2>
  <h3>{{ community.tagline }}</h3>
{% endfor %}
