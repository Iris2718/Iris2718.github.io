---
layout: page
title: Math & Physics
permalink: /math_physics/
---

Math things, physics things, related things, I hope you think they are cool!

<p>Posts in category "Math" are:</p>

<ul>
  {% for post in site.categories.Math %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

<p>Posts in category "Physics" are:</p>

<ul>
  {% for post in site.categories.Physics %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>