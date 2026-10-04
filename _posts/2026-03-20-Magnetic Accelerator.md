---
layout: post
title: "IYPT 2026 Problem 8: Magnetic Accelerator"
date: 2026-03-20 19:35:04 +0800
math: true
categories: [IYPT,CYPT,Physics]
tags: [IYPT,CYPT,Physics] 
media_subpath: /assets/img/20260320
image:
  path: title.jpg
---

Today I finally drawed a period to my second problem： Magnetic Accelerator. *Phew*
Here's the record I made during the process:
At the first glance of the problem, it seemed pretty intuitive to analyze it as a scenario with magnetic potential differences. However, the method to establish the potential difference was still unknown, so several pre-experiments had to be done to determine the proper arrangement of the magnets. In addition, since the cube magnets had to be kept in place during the acceleration process, the fixation of the magnets also posed a problem. I could not jut tape the cubes on the board since it would add complexity to explain the effects of the tape on the experiment data, nor could I glue them with hot melt adhesive which would not only render it difficult to rearrange the magnetics but also influence the eddy current produced.
Thus, I devised a creative solution: adhering another identical piece to the bottom of the magnets. Through this means, I only need to adjust the position and the magnitude of the magnetic moments without adding other complications to the situation. As for the pre-experiments, I designed four types of array: 
1. NS Alternating: The cube magnets all have their poles facing upward, but the north pole and the south pole alternates in the rows, forming a NS pattern.
2. N Facing upward: It was the same as the first one, but the poles facing upward are all north.
3. N facing outside: The magnets' north pole faced outside the metal board.
4. S Facing upward: The same as the second one except the poles facing upward are all south.
(The north poles of the magnetic discs that served as the wheels for the cart all faced inward. The numbers of the magnets used in each design are the same)
The procedure include fixing the magnets, installing a high-speed camera above the array, and placing the cart on the metal board. The cart's motion was recorded, and the resulting video was later imported into Tracker, an open-source video analysis and modeling software, for analysis.
After inspecting the data obtained from the tracker, I determined that the second design performed the best, so it became the setup for the formal experiment.
While working on the experiments, I simultaneously learned theory about magnetic moments, magnetic potential, eddy current etc. Taking the things I studied into account, I constructed a model that utilize magnetic potential wells to describe the acceleration mechanism. Think of the whole apparatus as a hill with slanted sides. The first row of magnets was the hill top, so placing a cart there would be similar to place a rock on the top of the hill. Because the cart would be in an unstable equilibrium, any small peturbation would cause it to "roll down the hill". However, the process was not smooth as there were several wells on the way down, so everytime the cart encounters a pair of magnets ahead, it would slow down a bit before it picked up speed again. This phenomenon could be easily understood because when the cart approached the magnets head on, the north poles of the cubes and the discs repelled each other, decelerating the cart, but when the cart glided past the cubes, it was again repelled(or to be exact propelled) to accelerate. 

The formal experiments resembled the pre-experiments. The only difference was that I changed the angle of the two rows of cubes and the number of magnet pairs on the board. 

After completing the theory and the experiments, the subsequent task was to simulate the curves predicted by the theory and compare them with the experimental data. I had to convert the Tracker data into a grid in order to plot them in Origin. Trust me, processing the data was not the most enjoyable part of the project. I had to try several modes of smoothing to smooth the experimental curves and scale it so that the positions of the potential well matches the theory curve to the greatest extent. Fortunatly, it did not take forever to deal with the data, so I managed to paste the processed curves on my reports in about three days. 
![picture 1](p1.jpg) ![picture 2](p2.jpg) 
![picture 3](title.jpg)
{% include embed/youtube.html id='TrzC6ErCnkU' %}
{% include embed/youtube.html id='18A2gI6Kxn8' %}
{% include embed/youtube.html id='D4HaOe4na-E' %}
{% include embed/youtube.html id='8qqh9B7J0rY' %}
{% include embed/youtube.html id='7THGufu0Ox8' %}
