# CONNECT 4

A two-player connect 4 game built in Python using Pygame. The game features a graphical board and pieces, hovering piece previews, and game statistics.

## How to Play

From the main menu, click "New Game". From there, an empty 7x6 board appears with a red tile hovering above. The player with the red pieces moves the mouse over the board, and the piece follows, hovering over the column the player's mouse is currently over. The red player drops the piece by clicking, and the piece falls into the lowest available slot on the board. It is now the yellow player's turn. They choose a column to drop their piece by clicking the mouse over their chosen column. Play continues until either one player lines up four of their coloured pieces vertically, horizontally, or diagonally - a "Connect 4", or until the entire board is filled - a draw.

Once the game ends, a pop-up window displays the result after a short delay. The players can then navigate back to the main menu, where they can play a new game, view the overall game statistics, or quit the programme.

## Requirements

- Python 3.x
- Pygame: `pip install pygame`

## How to Run

`python3 CONNECT_4.py`

## Features

- Win detection in all directions (vertical, horizontal, diagonal)
- Draw detection
- Hovering preview showing where your piece will fall
- Delayed pop-up window after the game ends
- Main menu screen for navigation
- Game statistics tracking total games played, red wins, yellow wins, draws, average moves, shortest game, longest game
- Stats screen
- Quit button

## Project Structure

- `CONNECT_4.py` - main game script
- `graphics/` - contains png files for the board slots, red piece, and yellow piece
- `fonts/` - contains the font used for text rendering

## Author

Louis Strehlow

## Date

16 July 2026

