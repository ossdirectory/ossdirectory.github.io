---
layout: page
title: 📅 Events
---
<ul>
  {% for post in site.posts %}
    {% if post.categories contains "events" %}
    <li>
      <a href=".{{ post.url }}">{{ post.date }} - {{ post.title }}</a>
    </li>
    {% endif %}
  {% endfor %}
</ul>
