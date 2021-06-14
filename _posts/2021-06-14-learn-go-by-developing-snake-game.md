---
layout: post
title: Learn Go by developing Snake game!
subtitle: Let's learn by doing
tags: [go]
comments: true
---

I am sure some of you remember the good old days where snakes were the only game in our smartphones. In this serie I will implement a Snake clone using GoLang. I want to have a nerdy version, so instead of having a graphical UI I will use bash terminal as UI.

## Let’s get started

First, let’s start with a plan. In all software projects, I like having milestones and iterations. In this project I will also have milestones that will give me the feeling of progress, this is critical to keep motivation above a certain level :)

![MVP](https://vitalitychicago.com/wp-content/uploads/2019/08/content_lean_kniberg.png){: .mx-auto.d-block :}
*Source: [YouTube](https://youtu.be/0P7nCmln7PM), Making Sense of MVP (Minimum Viable Product)*

I am thinking aloud
- I want to have a terminal based game, so my game-view should refresh periodically. A very similar example is the output of the unix top command.
  - M1: Have a simple program that prints Hello World 1, Hello World 2, Hello World 3…  without adding new lines to console output.
- I want to see if I can simulate the snake’s movement using the technique I proposed.
  - M2: Simulate a snake using predefined snapshots. There will be no user input but I will print the output in a way that you will see a moving snake
- First two milestones actually proves the concept; at this point I have no doubt that this will work :). Now I can move to the next milestones where I will implement controls, the game logic.
- Now it is time to use real data structures to model the snake, board and movement. There will be no user input but I will move the snake in the board programmatically.
  - M3: Programmatically move the snake in the board, i.e provide direction programmatically and verify that it moves in the board.
- Finally, get user keyboard inputs to move the snake in the board. This will give the expected user experience.
  - M4: Let the user play the game with keyboard keys.

By the end of M4 I will have the MVP of the game; and at each step I will see the progress.

This will be an exciting journey :)
