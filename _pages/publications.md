---
layout: archive
title: "Publications and preprints"
permalink: /publications/
author_profile: true
---

* Feng Shao and Guolei Zhong. Bigness of tangent bundles and dynamical rigidity of Fano manifolds of Picard number 1 (with an appendix by Jie Liu). arXiv:2311.15559.
  <br>[arXiv:2311.15559](https://arxiv.org/abs/2311.15559)
* Feng Shao and Guolei Zhong. Boundedness of finite morphisms onto Fano manifolds with large Fano index. <I><B>Journal of Algebra</B></I>, 639:678–707, 2024.
  <br>[doi:10.1016/j.jalgebra.2023.10.030](https://doi.org/10.1016/j.jalgebra.2023.10.030)&emsp;&emsp;[arXiv:2211.16380v2](https://arxiv.org/abs/2211.16380v2)
* Feng Shao. On pseudoeffective thresholds and cohomology of twisted symmetric tensor fields on irreducible Hermitian symmetric spaces.  <I><B>Science China Mathematics</B></I>, 2024.
  <br>[doi:10.1007/s11425-022-2186-6](https://doi.org/10.1007/s11425-022-2186-6)&emsp;&emsp;[arXiv:2012.11315](https://arxiv.org/abs/2012.11315)
* Andreas Höring, Jie Liu, and Feng Shao. Examples of Fano manifolds with non-pseudoeffective tangent bundle. <I><B>Journal of the London Mathematical Society</B></I>, 106:27–59, 2022.
  <br>[doi: 10.1112/jlms.12567.](https://doi.org/10.1112/jlms.12567)&emsp;&emsp;[arXiv:2003.09476](https://arxiv.org/abs/2003.09476)



{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
