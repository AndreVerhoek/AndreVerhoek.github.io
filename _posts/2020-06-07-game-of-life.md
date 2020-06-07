---
layout: post
title:  "Game of Life - John Conway"
date:   2020-06-07 13:54:00 +0200
tags: [Game of Life,automation]
comments: false
---

The Game of Life is a cellular automaton, devised by mathematician John Horton Conway (1937-2020) in 1970. The game of life consists out of a grid of cells, which are either dead or alive (their state). In the picture below, brown is alive and yellow is dead. Each cell has a neighbourhood, consisting of the surrounding cells. In the first generation (G0) the state is assigned randomly, each following generation follows a set of fixed rules (usually a mathematical function):

1.  Living cells die if they have fewer than 2 neighbours (underpopulation/loneliness)
2.  Living cells die if they have more than 3 neighbours (overpopulation)
3.  Dead cells that have 3 neighbours become alive (reproduction)
4.  Otherwise, there is no chance in state.

Applying that creates some great effects in a random world and is fun to play around with. I've created an RShiny tool to play around with different generations and sizes, feel free to have a [try](https://andreverhoek.shinyapps.io/GameOfLife/) or have a look at the [code](https://github.com/AndreVerhoek/game-of-life)).

![Example of Game of Life](https://media.giphy.com/media/Q5RoPWTdBUtyXjasPh/giphy.gif)
