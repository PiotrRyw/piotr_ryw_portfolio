---
layout: post
title:  "Fox fursuit"
date:   2026-07-08 10:52:00 +0200
categories: art
permalink: /art/2026/07/fox-fursuit.html
----------------------------------------

Fox fursuit presentation.

{% assign image_cat = "fox" %}
{% for file in site.static_files %}
{% if file.image and file.path contains image_cat %}
![Image]({{ file.path | relative_url }})
{% endif %}
{% endfor %}
------------
