---
layout: post
title:  "Jaw mechanism for masks"
date:   2026-07-08 10:48:00 +0200
categories: art
permalink: /art/2026/07/jaw-mechanism.html
---
A simple rotation mechanism for mounting as a jaw joint for head masks with movable jaw.
The rail assembly is separeted into three parts and positioned on a print bed in a way to ensure parallel print lines on the top surface, for minimal friction.

{% assign image_cat = "jaw" %}
{% for file in site.static_files %}
  {% if file.image and file.path contains image_cat %}
![Image]({{ file.path | prepend:site.baseurl }})
  {% endif %}
{% endfor %}
