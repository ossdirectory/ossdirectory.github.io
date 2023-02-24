---
layout: default
title: Communities
---
# Communities

<h2>via posts</h2>

<ul>
  {% for post in site.posts %}
    <li>
      <a href=".{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


<h2>via collections</h2>

{% for community in site.communities %}
  <h3>{{ community.title }}</h3>
{% endfor %}
