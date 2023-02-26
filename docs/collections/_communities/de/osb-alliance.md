---
title: "Open Source Business Alliance"
tagline: "Bundesverband für digitale Souveränität e.V."
layout: page
external-url: "https://osb-alliance.de"
external-logo: "https://osb-alliance.de/wp-content/uploads/2020/04/osba-logo-claim.svg"
---

[![]({{ page.external-logo }})]({{ page.external-url }})

{{ page.tagline }}

<h2>Posts</h2>

<ul>
  {% for post in site.categories.osb-alliance %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: site.minima.date_format }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
