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

**Journals**

**Xiong, R. M.**, Xie, T., Zhang, H., Li, T., Gong, G., Yu, X., & He, Y. (2022). The pattern of cortical thickness underlying disruptive behaviors in Alzheimer’s disease *Psychoradiology*, 2(3), 113–120. https://doi.org/10.1093/psyrad/kkac017.

Xu, Q., **Xiong, R. M.**, Zhao, M., & Wang, H. (2024). **The pattern of cortical thickness underlying disruptive behaviors in Alzheimer’s disease.** *Psychoradiology*. forthcoming.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}