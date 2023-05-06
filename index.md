---
layout: home
paginate: true
alt_title: "Basically Basic"
sub_title: "Your new default Jekyll theme"
introduction: |
  this is theme
---
{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}
