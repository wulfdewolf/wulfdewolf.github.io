---
layout: page
title: master's thesis
description: "Transfer learning in Brain-Computer Interfaces: Language-Pretrained Transformers for Classifying Electroencephalography"
img: assets/img/vub.png
importance: 1
category: work
---

This project was my master's thesis for the degree of MSc in Applied Sciences and Engineering: Computer Science, at the [Vrije Universiteit Brussel](https://www.vub.be/en).
I worked on transfer learning in Brain-Computer Interfaces (BCI).
In an [article](https://arxiv.org/abs/2103.05247) published by a collaboration between Facebook and Google, it was found that language-pretrained GPT2 could transfer to solving tasks unrelated to language, sometimes even without finetuning. The goal of my thesis was to verify how well it could classify electroencephalography (EEG, brain waves).
While the results were not spectacular, I did find some knowledge transfer from the language domain to the EEG domain.

I tried my very best to make the work as reproducible as possible.  
If you are interested, take a look at the GitHub page:
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center margin-bottom:1cm">
    {% include repository/repo.html repository="wulfdewolf/lpt-for-eeg" %}
    <br/><br/>
</div>
  
The thesis itself can be found [there](https://github.com/wulfdewolf/lpt-for-eeg/blob/main/thesis.pdf) there as well.  
Additionally, I published a summary of the results on [Weights & Biases](https://wandb.ai/wulfdewolf/lpt-for-eeg/reports/Transfer-Learning-in-Brain-Computer-Interfaces-Language-Pretrained-Transformers-for-Classifying-Electroencephalography--VmlldzoxOTIxNDU2).

An [extended abstract](https://bnaic2022.uantwerpen.be/wp-content/uploads/BNAICBeNeLearn_2022_submission_2852.pdf) of the thesis was accepted at [BNAIC](https://bnaic2022.uantwerpen.be/), where I presented it in a short talk.