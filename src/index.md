---
title: orpheus wisdom
layout: 'index.njk'
---

<ul>
  {% for post in collections.posts %}
  <li>
    <a href="{{ post.url }}">
      {{ post.data.title }}
    </a>
  </li>
  {% endfor %}
</ul>
