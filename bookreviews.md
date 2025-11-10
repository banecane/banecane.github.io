---
layout: default
title: "Book Reviews"
---

<h1>Book Reviews</h1>

<ul>
  {% for review in site.bookreviews %}
    <li>
      <a href="{{ review.url }}">{{ review.title }}</a> — {{ review.author }} ({{ review.rating }}/5)
    </li>
  {% endfor %}
</ul>
