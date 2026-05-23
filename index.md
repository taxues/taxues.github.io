---
layout: default
title: 首页
---

## 最新

<ul>
  {% for post in site.posts %}
    <li>{{ post.date | date: "%Y-%m-%d" }} - <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## 存档
* [收藏品](#)
* [2014 Isla Vista](#)
