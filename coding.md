---
title: "코딩"
permalink: /coding/
---
{% for post in site.categories.coding %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}