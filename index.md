---
layout: default
title: Home
---
# Welcome to My Blog
{% for post in site.posts %} 
- [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) — {{ post.date | date: "%b %d, %Y" }}
{% endfor %}
