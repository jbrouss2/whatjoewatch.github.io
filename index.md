---
layout: home
title: What Joe Watch
permalink: /
---

# Welcome to What Joe Watch
Just a girl who loves watching **tv shows and movies** and sharing my thoughts on them!

## Latest Reviews
{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

Enjoy exploring!