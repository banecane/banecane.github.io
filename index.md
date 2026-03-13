---
layout: home
title: My Notes Index
---

# My Mathematical Notes

<ul>
  {% for page in site.pages %}
    {% if page.title %}
      <li><a href="{{ page.url | relative_url }}">{{ page.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>