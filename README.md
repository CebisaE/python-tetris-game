#### Project Overview
This project is a Python implementation of the classic Tetris game using Pygame. It includes features such as sound effects. The game was developed following the tutorial by Code basics.

#### Installation
To install and run this Tetris game, follow these steps:

1. Clone the repository from GitHub:
   ```
   git clone https://github.com/CebisaE/python-tetris-game.git
   ```

2. Navigate into the project directory:
   ```
   cd python python-tetris-game
   ```

3. Install Pygame if you haven't already:
   ```
   pip install pygame
   ```

#### Usage
To start the game, run the following command:
```
python main.py
```

Controls:
- **Left Arrow**: Move piece left
- **Right Arrow**: Move piece right
- **Down Arrow**: Move piece down faster
- **Up Arrow**: Rotate piece clockwise
- **P**: Pause/unpause the game
- **R**: Restart the game

#### Project Structure
- `main.py`: Entry point of the game.
- `game.py`: Contains the main game loop and logic.
- `pieces.py`: Defines different Tetris pieces and their rotation logic.
- `constants.py`: Contains constants used throughout the game (e.g., screen size, colors).

#### Dependencies
- `pygame`: version 2.6.0

#### Game Mechanics
The game follows the standard Tetris rules where pieces fall from the top of the screen. Complete rows of blocks to clear them and earn points. The game ends when pieces stack up to the top of the screen.
