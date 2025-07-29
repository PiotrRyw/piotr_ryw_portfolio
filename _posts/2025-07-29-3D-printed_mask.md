---
layout: post
title:  "3D printed mask"
date:   2025-07-27 10:00:00 +0200
categories: art
permalink: /art/2025/07/3D-printed-mask.html
---
A fantasy horror creature mask. Designed, 3D printed, glued and painted.

{% assign image_cat = "Skull" %}
{% for file in site.static_files %}
  {% if file.image and file.path contains image_cat %}
![Image]{{ site.baseurl }}({{ file.path }})
  {% endif %}
{% endfor %}
