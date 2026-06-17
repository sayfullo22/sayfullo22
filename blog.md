---
layout: default
title: Blog
permalink: /blog/
---


# Writings

When engineering meets history, geography, and the long memory of civilizations.

{% for post in site.posts %}

## [{{ post.title }}]({{ post.url | relative_url }})

*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}

---

{% endfor %}

