# Turtle Crossing Game

A classic arcade-style crossing game built using Python's **Turtle** graphics framework. 

## How to Play
* **Objective:** Guide the green turtle from the bottom of the screen to the top finish line without colliding with moving cars.
* **Controls:** Press the `Spacebar` to move the turtle forward.
* **Progression:** Each successful crossing resets your position, advances you to the next level, and increases the speed of the traffic.
* **Game Over:** Collision with any car immediately ends the game.

## Project Structure
* `main.py` - The central game loop handling screen updates, collision detection, and level transitions.
* `player.py` - Manages the player's turtle avatar, starting position, and boundary detection.
* `car_manager.py` - Standardizes traffic generation, randomized colors, lane positioning, and speed increments.
* `scoreboard.py` - Tracks and displays the current level and renders the "GAME OVER" graphic canvas.