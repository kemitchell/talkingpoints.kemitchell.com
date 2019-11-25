---
title: Talking Points
layout: default
---

<ul>
{% for page in site.pages %}
  {% if page.indexed == true %}
  <li><a href="{{ page.url }}">{{ page.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>
