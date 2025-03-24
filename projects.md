---
title: "프로젝트"
permalink: /projects/
---
{% for post in site.categories.projects %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}