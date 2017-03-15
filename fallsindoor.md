---
layout: page
title: Falls Indoor
permalink: /fallsindoor/
---

Falls Indoor

<ul>
{% for team in site.data.fallsindoor.teams %}
  <li>
  <a href="https://github.com/{{ team.location }}">
      {{ team.name }}
  </a>
  </li>
{% endfor %}
</ul>
