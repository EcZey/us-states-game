# U.S. States Game

Welcome to the U.S. States Game! This game challenges you to name all 50 U.S. states. You can enter state names and see them displayed on a map of the United States. If you want to exit the game before finishing, you can do so, and the game will save the names of the states you missed.

## Project Overview

This project uses Python's `turtle` graphics library and the `pandas` library to create an interactive game where users guess U.S. states' names. The game displays a map of the United States with state names on it.

## Features

- **Interactive Map**: A map of the United States is displayed using a `.gif` image.
- **State Guessing**: Users can enter state names, which are then displayed on the map.
- **Exit Option**: Users can type "Exit" to stop the game and save the names of the states they missed.
- **Data Handling**: Uses `pandas` to manage state data and save missed states to a CSV file.

## Requirements

- Python 3.12
- `turtle` module (comes with Python standard library)
- `pandas` library (`pip install pandas`)

- **Note for macOS Users**: 
- Ensure you have Python and `pip` installed. If you are using Python 3, you might need to use `pip3` instead of `pip`:
  ```sh
  pip3 install pandas
## Usage

1. **Run the Game**:
   Execute `python main.py` to start the game.

2. **Game Instructions**:
   - A map of the United States will be displayed.
   - Type a state name in the prompt that appears.
   - If the entered state is correct, it will be displayed on the map.
   - Continue guessing until all 50 states are named or type "Exit" to stop the game.

3. **Exiting the Game**:
   - Type `Exit` in the prompt to end the game.
   - The names of the states you missed will be saved to `states_to_learn.csv`.

## Code Structure

- **`main.py`**: The main file that runs the U.S. States Game.
- **`50_states.csv`**: A CSV file containing the coordinates and names of all 50 U.S. states.
- **`blank_states_img.gif`**: An image file used as the background map of the U.S.

## Data Files

- **`50_states.csv`**: Contains columns `state`, `x`, and `y` for state names and their corresponding coordinates on the map.
- **`states_to_learn.csv`**: Created if the user exits the game with remaining states to learn. Contains the names of states that were not guessed.

## Object-Oriented Programming

This project does not use Object-Oriented Programming (OOP) principles; instead, it focuses on procedural programming to handle user input and map display.
