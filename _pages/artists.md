---
layout: page
title: The Artists
permalink: /artists/
---

<div class="posts">
  {% for post in site.posts %}
    <article class="post">
    {% if post.categories contains 'artistpage' %}
    {% include artistpost-grid.html %}
    {% endif %}
    </article>
  {% endfor %}
