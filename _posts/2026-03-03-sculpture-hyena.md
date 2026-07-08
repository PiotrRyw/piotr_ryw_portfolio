---
layout: post
title:  "Hyena Sculpture"
date:   2026-03-03 10:00:00 +0200
categories: art
permalink: /art/2025/07/sculpture-hyena.html
---
Hyena sculpture: Blender, PETG, resin print, acrylic paint.

{% assign image_cat = "sculpture001" %}
{% for file in site.static_files %}
  {% if file.image and file.path contains image_cat %}
![Image]({{ file.path | prepend:site.baseurl }})
  {% endif %}
{% endfor %}
