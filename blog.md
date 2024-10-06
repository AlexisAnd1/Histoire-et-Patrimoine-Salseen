---
layout: default
title: Blog
permalink: /blog/
---

<h1>Articles du Blog</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> - <em>{{ post.date | date: "%d %B %Y" }}</em>
    </li>
  {% endfor %}
</ul>
