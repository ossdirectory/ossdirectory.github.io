---
layout: page
title: 🧑‍💻 Jobs
---
<ul>
  {% for post in site.posts %}
    {% if post.categories contains "jobs" %}
    <li>
      <a href=".{{ post.url }}">{{ post.date }} - {{ post.title }}</a>
    </li>
    {% endif %}
  {% endfor %}
</ul>
