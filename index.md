---
layout: default
title: Home
---
# Welcome to My Blog
This is a test page.

{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%b %d, %Y" }}
{% endfor %}
