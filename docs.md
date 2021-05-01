---
layout: default
title: Documentation
permalink: /docs/index.html
---
<ul>
    {% for doc in site.docs %}
        <li><a href="{{doc.url}}">{{doc.title}}</a></li>
    {% endfor %}
</ul>