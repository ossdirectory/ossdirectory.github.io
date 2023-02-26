---
title: "OSSBIG Austria"
layout: page
tagline: "Open Source Software Business Innovation Group"
external-url: "https://www.ossbig.at"
external-logo: "https://www.ossbig.at/wp-content/uploads/2021/08/OSSBIG-Logo_WebStandard.png"
---

[![]({{ page.external-logo }})]({{ page.external-url }})

{{ page.tagline }}

<h2>Posts</h2>

<ul>
  {% for post in site.categories.ossbig %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: site.minima.date_format }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
