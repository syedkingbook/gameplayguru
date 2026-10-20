---
layout: default
title: Writing
permalink: /writing/
---

# Writing

Articles and thoughts on technical writing and programming:

{% for post in site.posts %}
* [{{ post.title }}]({{ post.url | relative_url }}) - *{{ post.date | date: "%b %d, %Y" }}*
{% endfor %}