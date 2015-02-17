---
layout: page
title: Archive
---

## Blog Posts

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
{% endfor %}