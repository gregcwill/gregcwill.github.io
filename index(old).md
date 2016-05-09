---
layout: page
title: Development Blog
---


<ul class="posts">
  {% for post in site.posts %}
    <h2><span></span><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h2>
    <p><span></span>{{ post.content }}</p>
  {% endfor %}
</ul>


