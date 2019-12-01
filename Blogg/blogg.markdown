---
layout: page
title: Blogg
permalink: /Blogg/
---
<h1>Here you can read all my blogg posts!</h1>

<ul class = "mybloggs">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>