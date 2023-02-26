---
title: "Open Source Business Alliance – Bundesverband für digitale Souveränität e.V."
layout: page
external-url: "https://osb-alliance.de"
---
[![](https://osb-alliance.de/wp-content/uploads/2020/04/osba-logo-claim.svg)]({{ page.external-url }})

<h2>Events</h2>

<ul>
  {% for post in site.categories.de.osb-alliance %}
    <li>
      <a href="{{ post.url }}">{{ post.date }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
