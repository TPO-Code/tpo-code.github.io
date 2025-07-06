---
layout: default
title: "Welcome"
---

# Welcome to My Blog

<div class="content-box">
  <p>This is a place where I document my projects, ideas, and updates. Explore my latest posts and projects to see what I've been working on.</p>
</div>

## Latest Posts

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span class="post-date">{{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>