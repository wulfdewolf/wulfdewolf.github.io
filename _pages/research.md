---
layout: page
permalink: /research/
title: Research
description:
categories: [Research,Theses]
nav: true
nav_order: 1
---

The following are some of my published works and articles. You can also find my profile on [Google Scholar](https://scholar.google.com/citations?hl=en&user=EphKDJ4AAAAJ) and [Semantic Scholar](https://www.semanticscholar.org/author/Wolf-De-Wulf/1958839977).

<!-- _pages/publications.md -->
{%- for y in page.categories %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

<h2 class="year">Teaching</h2>
<ul>
<li>
Tutor & marker. INFR11132 Machine Learning Practical. University of Edinburgh. 2023 Winter.
</li>
</ul>
