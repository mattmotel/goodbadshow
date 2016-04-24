---
layout: page
title: Good/Bad
permalink: /directory/
---

<p>Undeniably Good:</p>

<ul>
  {% for post in site.categories.good %}
    {% if post.url %}
        <li><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

<p>Undeniably Bad</p>

<ul>
  {% for post in site.categories.bad %}
    {% if post.url %}
        <li><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>