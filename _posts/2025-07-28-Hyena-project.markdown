---
layout: post
title:  "Hyena project"
date:   2025-07-28 10:07:00 +0200
categories: art
permalink: /art/2025/07/Hyena-project.html
---
A study on organic anatomy and Blender's hair system utilising Geometry Nodes.


{% assign image_cat = "Hyena" %}
{% assign subset = "artstation" %}
{% for file in site.static_files %}
  {% if file.image and file.path contains image_cat and file.path contains subset %}
![Image]{{ site.baseurl }}({{ file.path }})
  {% endif %}
{% endfor %}

{% assign image_cat = "Hyena" %}
{% assign subset = "wireframe" %}
{% for file in site.static_files %}
  {% if file.image and file.path contains image_cat and file.path contains subset %}
![Image]{{ site.baseurl }}({{ file.path }})
  {% endif %}
{% endfor %}
