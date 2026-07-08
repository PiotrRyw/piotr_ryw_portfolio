---
layout: post
title:  "Jaw mechanism for masks"
date:   2026-07-08 10:07:00 +0200
categories: art
permalink: /art/2026/07/jaw-mechanism.html
---
A simple rotation mechanism for mounting as a jaw joint for head masks with movable jaw.

{% assign image_cat = "jaw" %}
{% for file in site.static_files %}
  {% if file.image and file.path contains image_cat %}
![Image]({{ file.path | prepend:site.baseurl }})
  {% endif %}
{% endfor %}
