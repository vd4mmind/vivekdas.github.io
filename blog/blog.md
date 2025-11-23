---
layout: default
title: Blog
permalink: /blog/
---

## My Blog Snippets

<ul>
  {% for post in site.posts %}
    <li>
      <span style="color: #666; font-size: 0.8em;">{{ post.date | date: "%Y-%m-%d" }}</span>
      <br>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
    <br>
  {% endfor %}
</ul>

[← Back to Home]({{ site.baseurl }}/)
