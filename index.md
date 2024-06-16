---
layout: default
title: My Blog
---

# Welcome to My Blog

This is the main page of my blog.

## Posts

{% for post in site.posts %}
- {{ post.title }}
{% endfor %}
