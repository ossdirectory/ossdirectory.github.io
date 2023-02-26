---
layout: page
title: 📅 Events
---
<ul>
  {% for event in site.events %}
    <li>
      <a href=".{{ event.url }}">{{ event.date }} - {{ event.title }}</a>
    </li>
  {% endfor %}
</ul>
