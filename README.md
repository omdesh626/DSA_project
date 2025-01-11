# DSA_project


2048 Game Implementation in Python with tkinter
This repository contains an implementation of the popular 2048 game using Python and the Tkinter library. The game features a dynamic grid that updates in real-time as the player moves tiles, aiming to combine numbers to reach 2048.

Features
Dynamic UI: The game grid updates visually with each move.
Keyboard Controls: Use arrow keys to move tiles.
Winning and Losing States: The game detects when the player wins or loses.
Customizable Appearance: Colors, fonts, and grid sizes are configurable via constants.
Code Structure:-
Game2048 Class:
The Game2048 class is the core of the application. It manages the user interface, game state, and interactions. The class is broken down into the following components:

Initialization:

Sets up the game window with the title "2048".
Binds keyboard events for player input.
Initializes the game grid and matrix.
Grid Setup:

Creates the grid layout using Tkinter Frame and Label widgets.
Configures visual aspects such as background colors, fonts, and padding.
Matrix Initialization:

Initializes the 4x4 grid matrix using functions from LogicsFinal.
Adds two initial "2" tiles to the grid.
Grid Updates:

Dynamically updates the UI grid based on the current game state.
Colors and text adapt to the tile values.
Key Events:

Maps arrow key inputs to movement functions defined in LogicsFinal.
Updates the grid and checks for win or lose conditions after each valid move.
Dependencies:-
LogicsFinal: Contains the core game logic for movements, state checks, and tile generation.
constants.py: Holds constant values for grid dimensions, colors, fonts, and more.

How to download and run:-
Download all the files and place them in the same folder. Open the folder in Jupyter, and run the 2048.ipynb file. The 2048.ipynb file will automatically import the logicsfinal.py and constants.py files using the import function.
