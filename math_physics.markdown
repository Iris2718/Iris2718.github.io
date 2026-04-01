---
layout: page
title: Math & Physics
permalink: /math_physics/
---

Math things, physics things, related things, I hope you think they are cool!

Posts in category "Math" are:

{% for post in site.categories.Math %}
 + [{{ post.title }}]({{ page.url }})
{% endfor %}

Posts in category "Physics" are:

{% for post in site.categories.Physics %}
 + [{{ post.title }}]({{ page.url }})
{% endfor %}