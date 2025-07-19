---
layout: default
title: Blog
---

<h1>Blog</h1>

<ul>
  {% for post in site.posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%d %B %Y" }}</li>
  {% endfor %}
</ul>
