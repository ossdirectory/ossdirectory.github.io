---
layout: page
title: 🌟 Success-Stories
---
<ul>
  {% for story in site.stories %}
    <li>
      <a href=".{{ story.url }}">{{ story.date }} - {{ story.title }}</a>
    </li>
  {% endfor %}
</ul>