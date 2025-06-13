---
layout: default
title: Catatan Kertas
---

## Selamat datang di Catatan Kami, Segera tinggalkan tempat ini!

Berikut adalah tulisan terbaru:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> — <small>{{ post.date | date: "%d %B %Y" }}</small>
    </li>
  {% endfor %}
</ul>
