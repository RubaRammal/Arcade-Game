# Classic Arcade Game Clone

This project is part of Udacity's frontend nanodegree. An implementation of the classic arcade game Frogger.

## Installation

After cloning the project, you can run the game by simply openning index.html file in your browser.
The game will start once a player is selected and is played using the arrows on the keyboard.

## Instructions

### Select a player to start the game 

You can select a player by moving the players using the left and right arrows and pressing enter once the chosen player is standing above the star icon.

### Rules

1. A player can move in four directions, up, down, right and left.
2. A player must not collide with enemies (fly, ghost). If collision occurs, the player will lose a life (heart).
3. A player's score will increase if gems are collected or if the player reaches the water according to the following:
	..* Reach water: score will increase by 1 point.
	..* Collect blue gem: score will increase by 20 points.
	..* Collect orange gem: score will increase by 10 points.
	..* Collect green gem: score will increase by 5 points.
	..* Collect 5 keys and lives are full: score will increase by 100 points (see 4.).
4. A player has 3 lives initially, a collision with an enemy will cause the loss of a life. If a player collects 5 keys, lives will increase by 1.
5. If all lives are lost, the game will reset.
6. If the player reaches the water, only the location of the player will reset.

## Credits 

Game assets credit "Kenney.nl"

Copyright (c) 2017 Udacity