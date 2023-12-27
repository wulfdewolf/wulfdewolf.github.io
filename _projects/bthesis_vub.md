---
layout: page
title: bachelor's thesis
description: "LP2PB: Translating Answer Set Programs into Pseudo-Boolean Theories"
img: assets/img/vub.png
importance: 1
category: academic
---

This project was my bachelor's thesis for the degree of BSc in Computer Science, at the [Vrije Universiteit Brussel](https://www.vub.be/en).
I developed a tool that could translate Answer Set Programs (ASP) into pseudo-Boolean theories. 
The idea was that pseudo-Boolean solvers often implement the cutting plane proof system, which is stronger than the resolution proof system
that is often used in ASP solvers. Through the translation tool, ASP programs could be solved using the stronger proof system.
I evaluated a variety of competition benchmarks and found that performance was either equal or better, in some cases.

This project was my first real academic work, and I loved working on it.
I am very grateful for the supervision of Prof. Dr. Bart Bogaerts at the time.
He saw that I was interested and proposed to co-author a conference paper, in parallel with the bachelor's thesis.
While that introduced a lot more work, I could not say no to the opportunity.

The paper in question got accepted at [ICLP](https://iclp2020.unical.it/), at which I presented it in a talk.  
If you are interested, you can find the paper [here](https://cgi.cse.unsw.edu.au/~eptcs/paper.cgi?ICLP2020.25).  
Also, take a look at the GitHub repository:
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
    {% include repository/repo.html repository="wulfdewolf/lp2pb" %}
</div>
<br/>
Supervisors: [Prof. Dr. Bart Bogaerts](https://bartbogaerts.eu)
