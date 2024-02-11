---
layout: page
title: biomedical knowledge graph embeddings
description: "Knowledge Graph Embeddings in the Biomedical Domain: Are They Useful? A Look at Link Prediction, Rule Learning, and Downstream Polypharmacy Tasks"
img: assets/img/biokg.png
importance: 2
category: academic
---

This was a group project I worked on in the Master of Science by Research (MScR) degree part of the [UKRI CDT in Biomedical AI](https://web.inf.ed.ac.uk/cdt/biomedical-ai) at the [University of Edinburgh](https://www.ed.ac.uk/).
[Aryo Pradipta Gema](https://aryopg.github.io/), [Dominik Grabarczyk](https://linkedin.com/in/dominik-grabarczyk) and I evaluated a bunch of knowledge graph embedding (KGE) models on a very large biomedical knowledge graph (KG).
In the middle of the project, AstraZeneca published [a paper](https://www.sciencedirect.com/science/article/pii/S2667318522000071?via%3Dihub) that had the exact same goal for the exact same KG.
A bit of a hit in the face to see your research idea scooped from under your nose, but our models seemed to be performing much better than theirs on the same data, 
so we pushed on a wrote an article about our work.

By embedding these massive KGs in lower dimensions, we can predict links that are missing in the KGs:
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
    {% include repository/repo.html repository="wulfdewolf/lpt-for-eeg" %}
</div>
<br/>
Depending on the content of the KG, new-found links can help clinical research such as drug repurposing or predicting side effects of drug combinations.

The article is out as a preprint on [arXiv](https://arxiv.org/abs/2305.19979), and we've submitted it for publication in [Bioinformatics Advances](https://academic.oup.com/bioinformaticsadvances).
You can take a look at the GitHub repository here:
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
    {% include repository/repo.html repository="aryopg/biokge" %}
</div>

Supervisors: [Dr. Ajitha Rajan](https://homepages.inf.ed.ac.uk/arajan/), [Dr. Pasquale Minervini](http://www.neuralnoise.com/), [Dr. Antonio Vergari](http://nolovedeeplearning.com/) & [Dr. Javier Alfaro](https://scholar.google.pl/citations?user=ZUfjGcgAAAAJ)