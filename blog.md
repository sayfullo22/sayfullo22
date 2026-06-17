---

layout: default
title: Blog
-----------

# Writings

Thoughts on hydrology, water systems, environmental engineering, geography, and history.

{% raw %}{% for post in site.posts %}

## [{{ post.title }}]({{ post.url | relative_url }})

*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}

---

{% endfor %}{% endraw %}
