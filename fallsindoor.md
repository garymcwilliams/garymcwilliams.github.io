---
layout: page
title: Falls Indoor
permalink: /fallsindoor/
---

Falls Indoor

<ul>
{% for match in site.data.fallsindoor.matches %}
  <li>
      {{ match.date }} {{ match.home.name }} ({{ match.home.points }}) vs ({{ match.away.points }}) {{ match.away.name }}
  </li>
{% endfor %}
</ul>

<ul>
{% for team in site.data.fallsindoor.teams %}
  <li>
  <a href="https://github.com/{{ team.location }}">
      {{ team.name }}
  </a>
  </li>
{% endfor %}
</ul>
