---
layout: page
title: JOBS 🧑‍💻
---
<ul>
  {% for post in site.categories.jobs %}
    <li>
      <a href=".{{ post.url }}">{{ post.title }} - {{ post.date | date: site.minima.date_format }}</a>
    </li>
  {% endfor %}
</ul>
