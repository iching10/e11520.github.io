---
layout: default
title: Index
---

# Index

<ul>
{% for page in site.pages %}
  {% if page.url contains "/your-folder/" and page.name ends_with: ".md" %}
    <li><a href="{{ page.url }}">{{ page.name | replace: ".md", "" }}</a></li>
  {% endif %}
{% endfor %}
</ul>