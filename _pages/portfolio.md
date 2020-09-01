---
layout: archive
title: ""
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

**Research Projects**
======

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

