---
layout: page
title: Jobs 🧑‍💻
---
<ul>
  {% for post in site.categories.jobs %}
    <li>
      <a href=".{{ post.url }}">{{ post.date | date: site.minima.date_format }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
