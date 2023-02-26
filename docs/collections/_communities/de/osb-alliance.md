---
title: "Open Source Business Alliance"
tagline: "Bundesverband für digitale Souveränität e.V."
layout: page
external-url: "https://osb-alliance.de"
external-logo: "https://osb-alliance.de/wp-content/uploads/2020/04/osba-logo-claim.svg"
---

[![]({{ page.external-logo }})]({{ page.external-url }})

{{ page.tagline }}

<h2>Events</h2>

<ul>
  {% for post in site.categories.osb-alliance %}
    <li>
      <a href="{{ post.url }}">{{ post.date }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
