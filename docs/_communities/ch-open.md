---
title: "CH Open"
layout: page
description: "Verein zur Förderung von Open Source Software und offenen Standards in der Schweiz"
external-url: "https://www.ch-open.ch"
---

[![](https://www.ch-open.ch/wp-content/uploads/2019/04/logo_chopen_web_big-1.png)]({{ page.external-url }})

{{ page.description }}

<h2>Events</h2>

<ul>
  {% for post in site.categories.ch-open %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
