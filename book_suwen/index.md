---
layout: default
title: Index
---

# Index

{% assign md_files = site.static_files | where: "extname", ".md" %}
<ul>
{% for file in md_files %}
  {% if file.path contains "/your-folder/" %}
    <li><a href="{{ file.path }}">{{ file.name | replace: ".md", "" }}</a></li>
  {% endif %}
{% endfor %}
</ul>