---
layout: default
title: Blog
---

[Home]({{ '/' | relative_url }}) |
[Projects]({{ '/projects/' | relative_url }}) |
[Blog]({{ '/blog/' | relative_url }})

---

# Writings

Thoughts on hydrology, water systems, environmental engineering, geography, and history.

{% for post in site.posts %}

## [{{ post.title }}]({{ post.url | relative_url }})

*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}

---

{% endfor %}

