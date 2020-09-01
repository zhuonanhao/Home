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

<br>
<br>

**Course Projects**
======

{% for post in site.profolio-1 %}
  {% include archive-single.html %}
{% endfor %}

