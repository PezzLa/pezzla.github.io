---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
classes: wide
---

Here is where I shared my research during these years. Invited talks marked with an asterisk.

{% if site.talkmap_link == true %}
[See a map of all the places I've given a talk!](https://pezzla.github.io/talkmap/map.html)
{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single.html %}
{% endfor %}

