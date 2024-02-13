---
layout: default
permalink: /book/mengzi/
title: 孟子
---

<h2>{{ page.title }}</h2>
<ul>
    {% for article in site.mengzi %}
        <li><a class = "archive-link" href="{{ article.url }}">{{ article.title }}</a></li>
    {% endfor %}
</ul>