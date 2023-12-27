---
layout: page
title: creative chess
description: Producing Creative Chess through Chess Engine Selfplay
img: assets/img/chess.png
importance: 1
category: hobbies
---

This project was originally the assignment for the Computational Creativity course at the [Vrije Universiteit Brussel](https://www.vub.be).
The goal of the assignment was to design an application that implements any form of AI, to either be creative or help humans be creative.
In the report, we had to defend any creativity claims, using the frameworks existing computational creativity literature.
My idea consisted of forcing an existing chess engine (I chose [Stockfish](https://stockfishchess.org/)) to play more creative moves.
I designed a scoring scheme to evaluate whether or not creative moves were played, and I trained the weights for the forcing in a reinforcement learning manner.
In the end, I pitted two of the trained chess engines against each other and generated some weird and fun chess games.
I reasoned that by analysing these games, it could be possible to learn new chess lines/constructs.

At the end of the course, the lecturer ([Prof. Dr. Geraint Wiggins](https://ai.vub.ac.be/team/geraint-wiggins)) told us that [ICCC](https://computationalcreativity.net/iccc21/) had put out a call for short papers, of which the requirements corresponded
entirely with the assignment. I submitted my reformatted report and it got accepted. 
I presented the paper at the conference, in the form of a short talk.

While I think that this project was not groundbreaking nor very interesting for competitive chess players, it was fun to work on.
If you are interested, you can find the paper [here](https://computationalcreativity.net/iccc21/wp-content/uploads/2021/09/ICCC_2021_paper_77.pdf).  
Also, take a look at the GitHub repository:
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
    {% include repository/repo.html repository="wulfdewolf/creative-chess-producer" %}
</div>