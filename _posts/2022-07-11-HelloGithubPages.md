---
layout: single
title: "Hello Github Pages."
---

# KAIST16-Ryu의 첫 Github Pages Post 입니다.

<ul>
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
  {%endfor %}
</ul>
