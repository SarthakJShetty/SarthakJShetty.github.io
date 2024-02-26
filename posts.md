---
layout: page
title: Posts
permalink: /posts/
---

{% for post in site.posts %}
  <h2><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
  <p><em>Published on {{ post.date | date: "%B %d, %Y" }}</em></p>
{% endfor %}