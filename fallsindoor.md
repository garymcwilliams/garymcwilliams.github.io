---
layout: default
title: Falls Indoor
permalink: /fallsindoor/
---

Falls Indoor

|---
| Home                  | Pts                     | Pts                     | Away                  |
|-----------------------|------------------------:|:------------------------|----------------------:| {% for match in site.data.fallsindoor.matches %}
| {{ match.home.name }} | {{ match.home.points }} | {{ match.away.points }} | {{ match.away.name }} | {% endfor %}
