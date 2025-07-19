---
layout: default
title: Blog
---

<div class="container">
  <h1>{{ page.title }}</h1>

  <ul>
    {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%d %B %Y" }}
    </li>
    {% endfor %}
  </ul>
</div>
