---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


Journal Publications
======
* Zhou W, Hao Z, Gravish N. Collective synchronization of undulatory movement through contact[J]. Physical Review X, 2021, 11(3): 031051.

* Hao Z, Zhou W, Gravish N. Proprioceptive feedback design for gait synchronization in collective undulatory robots. Advanced Robotics, 2022.

