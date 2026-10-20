---
layout: default
nav_order: 1
nav_title: Home
---

# A place to keep track of my crafting projects and other thoughts.

## Latest posts

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url | relative_url }}), {{ post.date | date: "%b %-d, %Y" }}
{% endfor %}
