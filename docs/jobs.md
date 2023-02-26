---
layout: page
title: 🧑‍💻 Jobs
---
<ul>
  {% for job in site.jobs %}
    <li>
      <a href=".{{ job.url }}">{{ job.date }} - {{ job.title }}</a>
    </li>
  {% endfor %}
</ul>