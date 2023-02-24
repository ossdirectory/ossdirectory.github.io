---
layout: default
title: Communities
---
# Communities

<ul>
  {% for post in communities.posts %}
    <li>
      <a href=".{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
