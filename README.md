# Snake Game 🐍

## Overview
The Snake Game is a classic arcade game recreated using Python and Pygame. Players control a snake that grows in length as it consumes food, and the game ends when the snake collides with itself or the walls. This project demonstrates fundamental game development concepts and real-time interaction handling.

## Features
- **Classic Gameplay:** Players guide the snake to consume food and avoid obstacles.
- **Dynamic Food Generation:** Food spawns at random locations on the screen, avoiding the snake's body.
- **Score Display:** The current score (based on the snake's length) is displayed in real time.
- **Collision Detection:** The game ends if the snake collides with itself or the game window's boundaries.
- **Responsive Controls:** Arrow key inputs provide smooth and intuitive control over the snake's movement.

## Technologies Used
- **Python:** For implementing the game's logic and functionality.
- **Pygame:** For rendering graphics, managing user inputs, and handling animations.

## Methodology
The development process involved:

1. **Game Design:** Planned the layout, movement mechanics, and scoring rules.
2. **Initialization:** Set up the Pygame environment, game window, and initial game objects.
3. **Snake Movement:** Implemented smooth movement logic and real-time direction changes.
4. **Food System:** Added functionality to generate food at random, unoccupied positions.
5. **Collision Detection:** Designed logic to end the game upon collision with walls or the snake's body.
6. **Game Loop:** Created a loop to update and render the game state continuously.

## Workflow
1. **Initialization:**
    - Define game constants like window dimensions, block sizes, and snake speed.
    - Initialize Pygame and set up fonts for the score and game over messages.

2. **Game Objects:**
    - Create the snake as a list of blocks and food as a rectangle.
    - Update the snake's position based on player input.

3. **Collision Logic:**
    - Check for collisions with walls and the snake's body.
    - Handle food consumption and grow the snake.

4. **Rendering:**
    - Draw the snake, food, and score on the game window.
    - Update the display in each iteration of the game loop.
  
5. **User Input:**
    - Detect arrow key inputs to change the snake's direction.
    - Prevent invalid direction changes (e.g., reversing directly).
      
6. **Game Over:**
    - Display a "Game Over" message upon collisions.
    - Delay before closing the game.

## Result
- A fully functional Snake Game with smooth gameplay and responsive controls.
- Players can enjoy a retro-style gaming experience while improving their scores.
- The project serves as a great introduction to game development and Pygame's capabilities.
### Sample output
![Screenshot 2025-01-13 141545](https://github.com/user-attachments/assets/7df6b372-57fb-41dc-b8a8-7e72ba176b15)
![Screenshot 2025-01-13 141609](https://github.com/user-attachments/assets/7a3d8140-dac7-4542-b71e-9f761d40aa7a)
