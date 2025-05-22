---
# Feel free to add content and custom Front Matter to this file.

layout: page
title: S2P::Notes
---

{% for post in collections.posts.resources %}
  <p><a href="{{ post.relative_url }}">{{ post.data.title }}</a></p>
{% endfor %}
