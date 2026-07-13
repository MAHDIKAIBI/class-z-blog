---
layout: default
title: Class-Z Blog
---

# Welcome to Class-Z

Here are our latest articles:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      - <i>{{ post.date | date: "%B %e, %Y" }}</i>
    </li>
  {% endfor %}
</ul>
