---
layout: archive
title: "Recent research"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

(click heading for more detail)

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
