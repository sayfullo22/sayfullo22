---
layout: default
title: Blog
---

[Home]({{ '/' | relative_url }}) |
[Projects]({{ '/projects.html' | relative_url }}) |
[Blog]({{ '/blog.html' | relative_url }})

---

# Writings

Thoughts on hydrology, water systems, environmental engineering, geography, and history.

{% raw %}{% for post in site.posts %}

## [{{ post.title }}]({{ post.url | relative_url }})

*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}

---

{% endfor %}{% endraw %}
