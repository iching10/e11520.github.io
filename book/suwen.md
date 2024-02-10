---
layout: default
permalink: /book/suwen/
title: 素问
---

<h2>{{ page.title }}</h2>
<ul>
    {% for article in site.suwen %}
        <li><a class = "archive-link" href="{{ article.url }}">{{ article.title }}</a></li>
    {% endfor %}
</ul>