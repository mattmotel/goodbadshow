---
layout: page
title: Categories
permalink: /categories/
---


{% for category in site.categories %}
<a name="{{ category | first }}">{{ category | first }}</a>

<ul>
    {% for posts in category %}
    {% for post in posts %}
{% if post.title == null  %} {% else %}
<li><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
  {% endif %}
      {% endfor %}
    {% endfor %}
</ul>
{% endfor %}