---
title: Daily Log
layout: default
---

  <ul class="posts">
    {% for post in site.posts limit: 20 %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo;
      <a href="{{ post.url | prepend site.baseurl }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
