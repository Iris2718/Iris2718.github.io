---
layout: page
title: Math & Physics
permalink: /math_physics/
---

Math things, physics things, related things, I hope you think they are cool!

Posts in category "Math" are:


{% for post in site.categories.Math %}
   {% if post.url %}
      - [{{ post.title }}]({{ post.url }})
   {% endif %}
{% endfor %}


Posts in category "Physics" are:

{% for post in site.categories.Physics %}
   {% if post.url %}
       - [{{ post.title }}]({{ post.url }})
   {% endif %}
{% endfor %}