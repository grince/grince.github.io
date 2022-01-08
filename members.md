---
title: Mitglieder
author: Rince
---

<ul>
{% for member in site.data.members %}
  <li>
    <a href="https://github.com/{{ member.github }}">
      {{ member.name }}
    </a> {{member.band}}
  </li>
{% endfor %}
</ul>