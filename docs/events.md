---
layout: page
title: 📅 Events
---
<ul>
  {% for post in site.events %}
    <li>
      <a href=".{{ post.url }}">{{ post.date }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
