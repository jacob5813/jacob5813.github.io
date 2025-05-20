---
layout: default
title: home
---

# Welcome to My Site

Welcome to my personal site - **created with care** 

# Blog Posts

Check out my blog posts:

<ul>
  {% for post in site.posts  %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%Y-%m-%d" }}</li>
  {% endfor %}
</ul>
