# Pac-man-Game
A classic Pac-Man game built from scratch in Python using PyGame. Features include smooth player movement, AI-controlled ghosts with unique behaviors, collectible dots and power-ups, score tracking, and a fully designed maze. Learn object-oriented programming, collision detection, and basic AI while enjoying a fun retro game experience.

# Pac-Man in Python with PyGame

A classic Pac-Man game built from scratch using Python and PyGame! 🟡👻

## Overview
This project is a recreation of the iconic Pac-Man game. It includes player movement with smooth animation, AI-controlled ghosts with different behaviors (Blinky, Pinky, Inky, Clyde), collectible dots and power-ups, score tracking, lives, and a classic maze layout inspired by the original game. The game demonstrates object-oriented programming, collision detection, and basic AI logic in Python.

## Features
- Player movement using arrow keys
- Ghost AI with unique behaviors:
  - Blinky follows the player
  - Pinky ambushes the player
  - Inky uses complex targeting
  - Clyde alternates between chasing and roaming
- Collectible dots and power-ups
- Score system for dots, big dots, and ghosts
- Lives system (start with 3 lives)
- Fully designed maze with walls, corners, and gates

## Gameplay
- Objective: Eat all dots while avoiding ghosts
- Power-ups: Eating a big dot makes ghosts vulnerable temporarily
- Winning: Clear all dots to win
- Losing: Lose all lives to end the game

## Installation
1. Clone the repository:
```bash
git clone https://github.com/<your-username>/pacman-python.git
cd pacman-python

Install dependencies:
pip install pygame

Run the game:
python main.py

Controls
Arrow keys: Move Pac-Man
ESC: Quit game
Assets
All game images (player, ghosts, and power-ups) are stored in the assets/ folder:


assets/
player_images/  # Pac-Man animations
ghost_images/   # Blinky, Pinky, Inky, Clyde, power-ups
Make sure these images are present for the game to run correctly.

Contributing
Contributions are welcome. You can add new ghost behaviors, improve AI, enhance graphics, or fix bugs.

License
This project is licensed under the MIT License. You are free to use, modify, and distribute it for personal or educational purposes.

Enjoy playing classic Pac-Man in Python! 
