---
layout: page
title: 📅 Events
---
<ul>
  {% assign posts = site.posts | where:"category","events" %}
  {% for post in posts %}
    <li>
      <a href=".{{ post.url }}">{{ post.date }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
