# PACMAN Game

Welcome to the PACMAN game project! This repository contains the source code for a classic Pacman game built using HTML5, JavaScript, and CSS. 

## Project Structure

- **`index.html`**: The main HTML file that sets up the canvas and includes necessary scripts.
- **`css/`**: Contains stylesheets for the project.
  - `reset.css`: CSS reset file to ensure consistent styling across browsers.
  - `style.css`: Custom styles for the game.
- **`script/`**: Contains JavaScript files for different functionalities.
  - **`Utilities/`**: Utility scripts and constants.
    - `ImageConstants.js`: Constants related to images.
    - `GameMaps.js`: Functions for managing game maps.
    - `constants.js`: General constants used throughout the game.
    - `GameMode.js`: Handles game modes.
    - `Utils.js`: Utility functions.
    - `graph.js`: Functions for graph-related operations.
    - `astar.js`: Implementation of the A* pathfinding algorithm.
    - `AudioLoader.js`: Handles audio loading.
  - **`Components/`**: Scripts related to game components.
    - `GameMap.js`: Manages the game map.
    - `Sprite.js`: Manages sprite rendering.
  - **`Characters/`**: Scripts for game characters.
    - `GameActors.js`: Base class for game actors.
    - `Pacman.js`: Script for Pacman character.
    - **`Ghosts/`**: Scripts for different ghost characters.
      - `Ghosts.js`: Base class for ghost characters.
      - `Blinky.js`: Script for Blinky the ghost.
      - `Pinky.js`: Script for Pinky the ghost.
      - `Inky.js`: Script for Inky the ghost.
      - `Clyde.js`: Script for Clyde the ghost.
  - **`Components/`**: Additional game components.
    - `Game.js`: Main game logic.
    - `GameMenu.js`: Game menu logic.
    - `GameWorld.js`: Manages the game world.
  - **`script.js`**: Main JavaScript file that initializes and runs the game.

## How to Run

1. Clone the repository or download the project files.
2. Open `index.html` in a web browser that supports HTML5 canvas (e.g., Google Chrome, Firefox).

## Features

- Classic Pacman gameplay.
- Various ghost characters with different behaviors.
- Customizable game maps.
- Audio support for game sounds.

## Contributing

If you'd like to contribute to the project, feel free to fork the repository and submit pull requests. Please ensure your changes are well-documented and tested.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

Developed by Nikhil.

Enjoy the game!

