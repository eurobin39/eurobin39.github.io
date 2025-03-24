---
title: "공부"
permalink: /study/
---
{% for post in site.categories.study %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}