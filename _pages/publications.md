---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## 2023

**AUTOPLANBENCH: Automatically generating benchmarks for LLM planners from PDDL**<br>
*Katharina Stein and Alexander Koller*<br>
arXiv preprint arXiv:2311.09830<br>
[Link Paper](https://arxiv.org/abs/2311.09830)<br>
[Link Website](https://coli-saar.github.io/autoplanbench)


**From Sentence to Action: Splitting AMR graphs for Recipe Instructions**<br>
*Katharina Stein, Lucia Donatelli and Alexander Koller*<br>
Proceedings of the Fourth International Workshop on Designing Meaning Representations, pages 52-67, Nancy, France.<br>
[Link](https://aclanthology.org/2023.dmr-1.6/)



## 2021
**Representing Implicit Positive Meaning of Negated Statements in AMR**<br>
*Katharina Stein and Lucia Donatelli*<br>
Proceedings of the Joint 15th Linguistic Annotation Workshop (LAW) and 3rd Designing Meaning Representations (DMR) Workshop, pages 23–35, Punta Cana, Dominican Republic.<br>
[Link](http://dx.doi.org/10.18653/v1/2021.law-1.3)

**SHAPELURN: An Interactive Language Learning Game with Logical Inference**<br>
*Katharina Stein, Leonie Harter, and Luisa Geiger*<br>
Proceedings of the First Workshop on Interactive Learning for Natural Language Processing, pages 16–24, Online. Association for Computational Linguistics.<br>
[Link](http://dx.doi.org/10.18653/v1/2021.internlp-1.3)

**A Rose by Any Other Verb: The Effect of Expectations and Word Category on Processing Effort in Situated Sentence Comprehension**<br>
*Les Sikos, Katharina Stein and Maria Staudte*<br>
Frontiers in Psychology, Volume 12 <br>
[Link](https://doi.org/10.3389/fpsyg.2021.661898)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
