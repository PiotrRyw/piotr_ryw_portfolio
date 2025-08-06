---
layout: post
title:  "Hyena project"
date:   2025-07-28 10:07:00 +0200
categories: art
permalink: /art/2025/07/Hyena-project.html
---
A study on organic anatomy and Blender's hair system utilising Geometry Nodes.

{% assign image_cat = "Hyena" %}
{% for file in site.static_files %}
  {% if file.image and file.path contains image_cat %}
![Image]({{ file.path | prepend:site.baseurl }})
  {% endif %}
{% endfor %}
