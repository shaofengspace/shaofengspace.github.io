---
layout: archive
title: "Publications and preprints"
permalink: /publications/
author_profile: true
---

* Andreas Höring, Jie Liu, and Feng Shao. Examples of Fano manifolds with non-pseudoeffective tangent bundle. Journal of the London Mathematical Society, 106:27–59, 2022.
* Feng Shao. On pseudoeffective thresholds and cohomology of twisted symmetric tensor fields on irreducible Hermitian symmetric spaces. To appear in Science China Mathematics, 2023. 

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
