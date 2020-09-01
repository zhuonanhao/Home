---
layout: archive
title: ""
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

**Research Projects**
======

{% for portfolio-1.md in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

<br>
<br>

**Course Projects**
======

{% for post in site.portfolio/project %}
  {% include archive-single.html %}
{% endfor %}

dgdfghhhhhhhhhhhhhh
