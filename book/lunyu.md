---
layout: default
permalink: /book/lunyu/
title: 论语
---

<h2>{{ page.title }}</h2>
<ul>
    {% for article in site.lunyu %}
        <li><a class = "archive-link" href="{{ article.url }}">{{ article.title }}</a></li>
    {% endfor %}
</ul>