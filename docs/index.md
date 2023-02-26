---
layout: page
---
![](https://minio.digisus.ch/ossdirectory-assets/OSSD_Logo_rgb.svg)

{% include youtube.html id="DH3H8mkWHNk" %}

<h2>Premiummitglieder</h2>
<ul>
{% for member in site.data.ch.ch-open.members %}
  <li> {{ member.identifier }} </li>
{% endfor %}
</ul>
