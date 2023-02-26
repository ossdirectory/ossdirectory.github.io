---
layout: page
title: 🌟 Success-Stories
---
<ul>
  {% for post in site.posts %}
    {% if post.categories contains "stories" %}
    <li>
      <a href=".{{ post.url }}">{{ post.date }} - {{ post.title }}</a>
    </li>
    {% endif %}
  {% endfor %}
</ul>
