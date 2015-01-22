---
layout: default
title: "Selection of Tech Videos"
id: tech-videos
---

# Tech Videos

{% assign sorted_techvideos= (site.data.techvideos | sort: 'name') %}
{% for techvideo in sorted_techvideos %}

* <a href="{{ techvideo.url }}">{{ techvideo.name }}</a>

{% endfor %}