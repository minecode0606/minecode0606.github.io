---
title: Post Archive
layout: posts
paginate : true
permalink: /posts/
entries_layout: list
---
{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}
