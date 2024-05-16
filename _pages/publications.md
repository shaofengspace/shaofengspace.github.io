---
layout: archive
title: "Publications and preprints"
permalink: /publications/
author_profile: true
---

* Andreas H\"{o}ring, Jie Liu, and Feng Shao. Examples of Fano manifolds with non-pseudoeffective tangent bundle. \textit{\textbf{Journal of the London Mathematical Society}}, 106:27–59, 2022. 

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
