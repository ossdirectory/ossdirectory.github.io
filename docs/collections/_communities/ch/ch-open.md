---
title: "CH Open"
layout: page
tagline: "Verein zur Förderung von Open Source Software und offenen Standards in der Schweiz"
external-url: "https://www.ch-open.ch"
external-logo: "https://www.ch-open.ch/wp-content/uploads/2019/04/logo_chopen_web_big-1.png"
---

[![]({{ page.external-logo }})]({{ page.external-url }})

{{ page.tagline }}

<h2>Posts</h2>

<ul>
  {% for post in site.categories.ch-open %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: site.minima.date_format }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
