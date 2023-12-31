---
layout: page
permalink: /research/
title: Research
description:
categories: [Publications,Theses]
nav: true
nav_order: 1
---

The following are some of my published works and articles.  
You can also find my profile on [Google Scholar](https://scholar.google.com/citations?hl=en&user=EphKDJ4AAAAJ) and [Semantic Scholar](https://www.semanticscholar.org/author/Wolf-De-Wulf/1958839977).

<div class="research" >
    {%- for y in page.categories %}
      <h2 class="category">{{y}}</h2>
      {% bibliography -f papers -q @*[category={{y}}]* %}
    {% endfor %}
</div>
