---
layout: page
title: Good/Bad
permalink: /directory/
---

<p>Things that are good</p>

<ul>
  {% for post in site.categories.good %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.topic }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

<p>Things that are bad</p>

<ul>
  {% for post in site.categories.bad %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.topic }}</a></li>
    {% endif %}
  {% endfor %}
</ul>