---
layout: default
title: Falls Indoor
permalink: /fallsindoor/
---

Falls Indoor

|---
| Date             | Pts                     | Pts                     | Away                  |
|------------------|------------------------:|:------------------------|----------------------:|
{% for match in site.data.fallsindoor.matches %}
| {{ match.date }} | {{ match.home.name }} | {{ match.home.points }} | {{ match.away.points }} | {{ match.away.name }} |
{% endfor %}
