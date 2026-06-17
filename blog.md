---
layout: default
title: Blog
permalink: /blog/
---


# Writings

Thoughts on hydrology, water systems, environmental engineering, geography, and history.

{% for post in site.posts %}

## [{{ post.title }}]({{ post.url | relative_url }})

*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}

---

{% endfor %}

