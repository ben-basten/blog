---
title: "BS Scrabble"
description: "2 player multiplayer Scrabble knockoff game."
technologies: ["vue", "javascript", "websockets"]
repo: "https://github.com/ben-basten/bs-scrabble"
draft: false
---

![Game board screenshot](/images/projects/bs-scrabble.png)

## Overview

One of my absolute favorite courses at NMU was "Client-Side Programming". This purpose of this class was to introduce a variety of topics in modern web development, including JavaScript best practices, websockets, Vue.js, and creating basic web servers with Express.

For the final project of this class, we were tasked with creating a web app of our choosing. Partnering up with my friend Sam, we chose to create a Scrabble knockoff game. My role in the project was to design the user interface and setup the architecture for the JavaScript under the hood.

## Technologies

* **Vue.js**: frontend framework we used to build the game.
* **Socket.IO**: the JavaScript framework for implementing WebSockets. WebSockets were used to communicate game events realtime between clients such as changing your username, switching turns, and updating the score/game board.
* **CSS**: styling for the user interface.