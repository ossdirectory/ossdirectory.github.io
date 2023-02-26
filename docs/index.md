---
layout: page
---
![](https://minio.digisus.ch/ossdirectory-assets/OSSD_Logo_rgb.svg)

## Premiummitglieder

<ul>
{% for member in site.data.ch.ch-open.members %}
  <li> <a href="{{ site.url }}/vendors/{{ member.country }}/{{ member.identifier }}.html">{{ member.name }}</a> </li>
{% endfor %}
</ul>

## Über Uns

Das OSS Directory ermöglicht das einfache Auffinden von kompetenten Anbietern, die professionellen Support für Open Source Software erbringen.

Die Open Source Anbieter zeigen mittels Success Stories auf, bei welchen Nutzern (Kunden) sie bestimmte Open Source Produkte eingeführt haben. Damit besteht das OSS Directory heute aus einer umfangreichen Datenbank von mehreren Hundert Anbietern, die Dienstleistungen für rund 1000 Produkte erbringen. Insgesamt sind mehrere Hundert Nutzer erfasst, bei denen rund 500 Success Stories umgesetzt worden sind. Täglich greifen über 100 Unique Visitors auf das Verzeichnis zu, das sowohl auf Deutsch als auch auf Französisch und Englisch verfügbar ist.

Das OSS Directory wurde 2004 durch den Schweizer Open Source Förderverein [CH Open](https://www.ch-open.ch) gestartet und wurde im 2021 durch die Forschungsstelle Digitale Nachhaltigkeit der Universität Bern neu entwickelt und lanchiert.

Der Quellcode wird in einer eigenen [Github-Organisation von CH Open](http://github.com/ossdirectory/) veröffentlicht. Schon heute können dort entsprechende Bug Reports und Feature Requests eingegeben werden.

### Video

{% include youtube.html id="DH3H8mkWHNk" %}
