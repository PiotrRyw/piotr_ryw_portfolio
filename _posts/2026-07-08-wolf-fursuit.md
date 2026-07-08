---
layout: post
title:  "Wolf fursuit head - early design"
date:   2026-07-08 09:00:00 +0200
categories: art
permalink: /art/2026/07/wolf-fursuit.html
---
Wolf fursuit. Early visualisation of head design concept.

{% assign image_cat = "wolf_fursuit" %}
{% for file in site.static_files %}
  {% if file.image and file.path contains image_cat %}
![Image]({{ file.path | prepend:site.baseurl }})
  {% endif %}
{% endfor %}
