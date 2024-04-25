---
layout: page
title: Tweaks
permalink: /tweaks/
---

<h2>{{ site.data.sidebar.title }}</h2>
<ul>
    {% for item in site.data.sidebar.children %}
      <li><a href="{{ item.url }}">{{ item.title }}</a></li>
    {% endfor %}
</ul>