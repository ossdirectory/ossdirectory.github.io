---
layout: page
title: Success-Stories 🌟
---
<ul>
  {% for post in site.categories.stories %}
    <li>
      <a href=".{{ post.url }}">{{ post.date | date: site.minima.date_format }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
