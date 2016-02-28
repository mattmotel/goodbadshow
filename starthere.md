---
layout: page
title: Where to Start
permalink: /starthere/
---

<p>Start with these episodes</p>

<ul>
  {% for post in site.categories.starthere %}
    {% if post.url %}
        <li><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

