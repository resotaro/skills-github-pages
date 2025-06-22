---
title: こんにちは！ リゾ太郎です
---

<img src="./images/garaken-podcastJ.jpg" />

## このホームページについて

（工事中）

## リゾ太郎について

（工事中）

## 新着記事

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> <small>{{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>
