---
layout: default
title: Artikel
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> - {{ post.date | date: "%d %B %Y" }}
    </li>
  {% endfor %}
</ul>
