---
layout: archive
title: "Publications and preprints"
permalink: /publications/
author_profile: true
---

* Andreas Höring, Jie Liu, and Feng Shao. Examples of Fano manifolds with non-pseudoeffective tangent bundle. <I><B>Journal of the London Mathematical Society</B></I>, 106:27–59, 2022.
  <p>dds </p>
* Feng Shao. On pseudoeffective thresholds and cohomology of twisted symmetric tensor fields on irreducible Hermitian symmetric spaces. To appear in <I><B>Science China Mathematics</B></I>, 2023.
* Feng Shao and Guolei Zhong. Boundedness of finite morphisms onto Fano manifolds with large Fano index. <I><B>Journal of Algebra</B></I>, 639:678–707, 2024.
* Feng Shao and Guolei Zhong. Bigness of tangent bundles and dynamical rigidity of Fano manifolds of Picard number 1 (with an appendix by Jie Liu). arXiv:2311.15559.

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
