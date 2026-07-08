---
layout: post
title:  "Stoat Relief"
date:   2026-07-03 10:00:00 +0200
categories: art
permalink: /art/2026/07/stoat-relief.html
---
Stoat relief designed in Blender, 3D printed in PETG and painted using acrylics.

{% assign image_cat = "stoat-relief" %}
{% for file in site.static_files %}
  {% if file.image and file.path contains image_cat %}
![Image]({{ file.path | prepend:site.baseurl }})
  {% endif %}
{% endfor %}
