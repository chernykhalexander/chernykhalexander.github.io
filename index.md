---
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
title: Alexander Chernykh
---

{% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
