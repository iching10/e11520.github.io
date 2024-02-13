---
layout: default
permalink: /book/liji/
title: 礼记
---

<h2>{{ page.title }}</h2>
<ul>
    {% for article in site.liji %}
        <li><a class = "archive-link" href="{{ article.url }}">{{ article.title }}</a></li>
    {% endfor %}
</ul>