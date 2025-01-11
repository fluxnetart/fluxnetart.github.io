---
layout: page
title: News and Stories
permalink: /news/
---
{% for post in site.posts %}
{% if post.categories contains 'news' %}
{% include post-grid.html %}
{% endif %}
{% endfor %}

<div style="display: flex; align-items: center; justify-content: center; padding-top: 10px;">
    <img src="https://fluxnetart.github.io/images/insta.png" style="margin-right: 10px;">
    <p style="margin: 0;">follow us <a href="https://www.instagram.com/fluxnet.art/">@fluxnet.art</a></p>
</div>
