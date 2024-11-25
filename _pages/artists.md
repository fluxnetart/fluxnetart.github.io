---
layout: page
title: The Artists
permalink: /artists/
---

{% for post in site.posts %}
{% if post.categories contains 'artistpage' %}
{% include artistpost-grid.html %}
{% endif %}
{% endfor %}
