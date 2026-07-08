---
layout: post
title:  "Fox fursuit"
date:   2026-07-08 10:55:00 +0200
categories: art
permalink: /art/2026/07/fox-fursuit.html
featured: true
image: /assets/img/fox_fursuit_001.jpg
---
Fox fursuit presentation.

{% assign image_cat = "fox" %}
{% for file in site.static_files %}
  {% if file.image and file.path contains image_cat %}
![Image]({{ file.path | prepend:site.baseurl }})
  {% endif %}
{% endfor %}
