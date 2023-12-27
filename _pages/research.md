---
layout: page
permalink: /research/
title: Research
description:
categories: [publications,theses]
nav: true
nav_order: 1
---

The following are some of my published works and articles.  
You can also find my profile on [Google Scholar](https://scholar.google.com/citations?hl=en&user=EphKDJ4AAAAJ) and [Semantic Scholar](https://www.semanticscholar.org/author/Wolf-De-Wulf/1958839977).

<div class="publications" >
    {%- for y in page.categories %}
      <h2 class="category">{{y}}</h2>
      {% bibliography -f papers -q @*[category={{y}}]* %}
    {% endfor %}

    <h2 class="category">Teaching</h2>
    <ul>
    <li>
    Tutor & marker. Machine Learning & Pattern Recognition. 2023 University of Edinburgh.
    </li>
    </ul>
</div>
