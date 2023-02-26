---
layout: page
title: Events 📅
---
<ul>
  {% for post in site.categories.events %}
    <li>
      <a href=".{{ post.url }}">{{ post.date | date: site.minima.date_format }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
