# PacMen Factory

This code represents a PacMen Factory that generates and controls PacMen entities in a game environment.

## Overview

The PacMen Factory consists of the following components:

- A set of PacMan images represented by the `pacArray` variable.
- Variables `pos`, `direction`, and `pacMen` used for tracking the position, direction, and collection of PacMen entities.
- The `setToRandom` function that returns an object with random x and y coordinates within a specified scale.
- The `makePac` function, which creates a new PacMan entity by adding an image element to the HTML document.
- The `update` function, responsible for updating the position of each PacMan entity and checking for collisions with the boundaries of the game.
- The `checkCollisions` function, which detects collisions with the game boundaries and adjusts the PacMan's velocity accordingly.
- The `makeOne` function, which adds a new PacMan entity to the `pacMen` collection.

## Usage

To utilize the PacMen Factory, follow these steps:

1. Load the necessary PacMan images into the `pacArray` variable. Ensure that each image file path is correctly defined.

2. Call the `makeOne` function whenever you want to add a new PacMan entity to the game.

3. Use the `startGame` function to initiate the movement of all available PacMen entities.

4. Observe as the PacMen entities move within the game environment, bouncing off any boundary they encounter.

## License

This project is licensed under the [MIT License](https://opensource.org/license/mit/). 
