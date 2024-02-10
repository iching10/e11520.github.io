---
layout: default
title: Suwen
---

{% for post in site.suwen %}
  <h2>
    <a href="{{ suwen.url }}">
      {{ suwen.title }}
    </a>
  </h2>
  <p>{{ suwen.content | markdownify }}</p>
{% endfor %}