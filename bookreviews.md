---
layout: page
title: Book Reviews
permalink: /bookreviews/
---
<h1>Book Reviews</h1>

<ul>
  {% for review in site.bookreviews %}
    <li>
      <a href="{{ review.url }}">{{ review.title }}</a>
      <small>({{ review.date | date: "%b %d, %Y" }})</small>
    </li>
  {% endfor %}
</ul>
