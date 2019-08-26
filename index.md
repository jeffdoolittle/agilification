---
layout: page
title: Welcome
tagline: The art of being agile
---
{% include JB/setup %}

## Welcome!

This site is all about being agile. Not "doing" a process called "Agile," but actually developing and operating in an agile manner.

Agile is an adjective, not a noun.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
