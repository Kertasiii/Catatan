---
layout: page
title: Kategori
---
{% for category in site.categories %}
- {{ category[0] }}
{% endfor %}
