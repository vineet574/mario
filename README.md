# Simple Platformer Game

## Overview
This is a basic platformer game written in Java, where the player controls a character (represented as a red square) that can jump over obstacles and move within a predefined environment. The game simulates gravity and jumping mechanics to provide a simple and interactive experience.

## Features
- **Jumping Mechanic:** The character can jump when the player presses the `SPACE` key.
- **Gravity Simulation:** The character naturally falls back to the ground after jumping.
- **Basic Graphics:** Simple shapes and colors represent the player and the ground.

## How to Run
1. Copy the `SimplePlatformer` Java code into a Java development environment (like IntelliJ IDEA, Eclipse, or NetBeans).
2. Compile and run the program.
3. A window will appear with the game. Use the `SPACE` key to jump!

## Controls
- Press `SPACE` to make the character jump.

## Requirements
- Java Development Kit (JDK) installed (version 8 or later).
- Any IDE or text editor to write and run the Java code.

## Future Enhancements
- Add moving platforms and obstacles.
- Introduce enemies or collectibles (e.g., coins, stars).
- Improve character design with animations.
- Implement scoring and level progression.


Here are some new features added to your simple platformer:

✅ New Features:
Left/Right movement (←, → arrow keys).

Platform boundaries — Player can't go off-screen.

Double jump support.

Score — Based on how long the player survives.

Improved jump physics.

✅ How to Play:
← / → to move.

SPACE to jump.

Double jump is allowed once in air.

Score increases over time.


Added Features:
Collectible Coins: Players can collect coins to increase their score.

Obstacles: Avoid obstacles that deduct points if hit.

Game Over Condition: Ends the game if the player collides with an obstacle.

Restart Option: Allows the player to restart the game.




Features Explained:
Coins: Yellow circles the player can collect to gain points.

Obstacles: Black squares that end the game on collision.

Game Over: Displays "Game Over!" with a restart message when the player hits an obstacle.

Restart: Press "R" to restart the game, resetting all variables and regenerating coins and obstacles.

New Features Added:
Power-Ups: These are small pink circles that appear on the screen. When the player character touches one, it activates a speed boost.


Speed Boost: When a player collects a power-up, their movement speed increases, allowing them to move faster.

Game Feedback: A message is displayed on the screen when the speed boost is active.
 New Features Added:
Health System

Enemy Characters

Timed Power-Ups

Pause/Resume Feature

Background Music Toggle (structure only, no audio engine)

 Features Summary:
Jump + Double Jump

Coins, Obstacles, Power-Ups

Enemies with movement

Speed boost

Invincibility after hit

Timer & Health system

Pause and Restart

Checkpoint & Level system

