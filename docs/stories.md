---
layout: page
title: Success-Stories 🌟
---
<ul>
  {% for post in site.categories.stories %}
    <li>
      <a href=".{{ post.url }}">{{ post.title }} - {{ post.date | date: site.minima.date_format }}</a>
    </li>
  {% endfor %}
</ul>
