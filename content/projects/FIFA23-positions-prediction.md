+++
date = 2024-08-11
title = "FIFA 23 positions prediction"

[extra]
authors = "Matheus do Ó"
where = "Final project for the Introduction to Machine Learning Subject"
link = "https://github.com/Mth0/Predizendo-Posicoes-FIFA23"
#pdf =
+++

FIFA 23 is an eletronic football game in which you can play with different teams and players. Players have stats and the question this project raises is: Can I infer the position of a player only based on his stats? The question is yes! And it does make sense: Fowards tend to have high attacking stats and low defensive ones. The opposite to defenders.

This project models it in three ways:

- Using a simple neural network which get as input the stats of a player and outputs his position;
- A Random forest which tries to infer the positions based on their stats;
- (An ensemble) A random forest specialized in defining if a player is from an attacking or defensive position; And two neural networks: One specialized in attacking positions and other in defensive ones. Based on the answer of the random forest, the player is led to its corresponding neural network.

Which do you think that did perform better?
