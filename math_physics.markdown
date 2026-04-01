---
layout: page
title: Math & Physics
permalink: /math_physics/
---

Math things, physics things, related things, I hope you think they are cool!

## Math

{% for post in site.categories.Math %}
 + [{{ post.title }}]({{ post.url }})
{% endfor %}

## Physics

{% for post in site.categories.Physics %}
 + [{{ post.title }}]({{ post.url }})
{% endfor %}