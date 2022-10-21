Overview

Cycle is a game where the players try to cut each other off using cycles that leave a trail behind them.

Rules

Cycle is played according to the following rules.

Players can move up, down, left and right...
Player one moves using the W, S, A and D keys.
Player two moves using the I, K, J and L keys.
Each player's trail grows as they move.
Players try to maneuver so the opponent collides with their trail.
If a player collides with their opponent's trail...
A "game over" message is displayed in the middle of the screen.
The cycles turn white.
Players keep moving and turning but don't run into each other.

python3 -m pip install raylib

python3 Cycle

You can also run the program from an IDE like Visual Studio Code. Start your IDE and open the 
project folder. Select the main module inside the hunter folder and click the "run" icon.

## Project Structure
---
The project files and folders are organized as follows:
root (project root folder) +--main.py (program entry point) +--README.md (general info) +--constants.py (general info) +--game/ +--casting/ +--actor.py (game class with methods) +--cast.py (game class with methods) +--food.py (game class with methods) +--score.py (game class with methods) +--cycle.py (game class with methods) +--directing/ +--director.py (game class with methods) +--scripting/ +--action.py (game class with methods) +--control_actors_action.py (game class with methods) +--draw_actors_action.py (game class with methods) +--handle_collisions_action.py (game class with methods) +--move_actors-action.py (game class with methods) +--script.py (game class with methods) +--services/ +--keyboard-services.py (game class with methods) +--video-service.py (game class with methods) +--shared/ +--color.py (game class with methods) +--point.py (game class with methods)


## Required Technologies
---
* Python 3.10.1
* raylib

## Authors
---
* [Jose Herrera](her22023@byui.edu) 
