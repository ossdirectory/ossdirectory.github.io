---
layout: default
title: Communities
---
# Communities

<ul>
  {% for post in site.posts %}
    <li>
      <a href=".{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

{% for community in site.communities %}
  <h2>{{ community.title }}</h2>
{% endfor %}
