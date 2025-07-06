---
layout: default
title: "Welcome"
---

# Welcome to My Blog

This is a place where I document my projects, ideas, and updates.

## Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      - <span class="post-date">{{ post.date | date: "%d-%m-%Y" }}</span>
    </li>
  {% endfor %}
</ul>