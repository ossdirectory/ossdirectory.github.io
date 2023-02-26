---
title: "CH Open"
layout: page
description: "Verein zur Förderung von Open Source Software und offenen Standards in der Schweiz"
external-url: "https://www.ch-open.ch"
external-logo: "https://www.ch-open.ch/wp-content/uploads/2019/04/logo_chopen_web_big-1.png"
identifier: "ch.ch-open"
---

[![](page.external-logo)]({{ page.external-url }})

{{ page.description }}

<h2>Events</h2>

<ul>
  {% for post in site.categories.{{ page.identifier }} %}
    <li>
      <a href="{{ post.url }}">{{ post.date }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>