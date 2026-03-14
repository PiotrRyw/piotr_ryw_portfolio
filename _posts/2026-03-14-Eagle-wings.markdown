---
layout: post
title:  "Eagle wing"
date:   2026-03-14 10:07:00 +0200
categories: art
permalink: /art/2025/07/eagle-wings.html
---
Eagle inspired wings design using procedural textures.

{% assign image_cat = "eagle_wing" %}
{% for file in site.static_files %}
  {% if file.image and file.path contains image_cat %}
![Image]({{ file.path | prepend:site.baseurl }})
  {% endif %}
{% endfor %}

{% assign image_cat = "feather_shader_nodes" %}
{% for file in site.static_files %}
  {% if file.image and file.path contains image_cat %}
![Image]({{ file.path | prepend:site.baseurl }})
  {% endif %}
{% endfor %}
