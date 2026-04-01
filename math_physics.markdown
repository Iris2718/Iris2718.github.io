---
layout: page
title: Math & Physics
permalink: /math_physics/
---

Math things, physics things, related things, I hope you think they are cool!

Posts in category "Math" are:</p>


{% for post in site.categories.Math %}
   {% if post.url %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
   {% endif %}
{% endfor %}


Posts in category "Physics" are:

{% for post in site.categories.Physics %}
   {% if post.url %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
   {% endif %}
{% endfor %}