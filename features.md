---
layout: page
title: Features
permalink: /features/
---

<ol>
    {% for item in site.data.sidebar.children %}
      <li><a href="{{ item.url }}">{{ item.title }}</a></li>
    {% endfor %}
</ol>