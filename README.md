# Minesweeper AI

## Project Description
This project implements an AI to play the classic Minesweeper game that wins almost every time. Minesweeper is a puzzle game consisting of a grid of cells, where some contain hidden “mines.” Clicking on a cell that contains a mine detonates the mine and causes the user to lose the game. Clicking on a “safe” cell (i.e., a cell that does not contain a mine) reveals a number that indicates how many neighboring cells – where a neighbor is a cell that is one square to the left, right, up, down, or diagonal from the given cell – contain a mine. The AI uses propositional logic and knowledge inference to make decisions, aiming to safely navigate the minefield without detonating any mines. Note that it will not always win! In some cases, the AI must guess because it lacks sufficient information to make a safe move. This is to be expected. runner.py will print in the terminal whether the AI is making a move it believes to be safe or whether it is making a random move.

## Features
- **AI Game Logic**: Utilizes a knowledge-based approach to identify safe cells and mines.
- **Efficient Knowledge Representation**: Represents the game state with logical sentences, enabling the AI to make informed decisions.
- **Interactive GUI**: Built with Pygame, providing a visual and interactive interface for playing Minesweeper.
- **Safe Move and Random Move Capabilities**: The AI can make safe moves based on its knowledge or random moves when necessary.

## Technologies Used
- Python
- Pygame for GUI implementation
- Logical inference for AI decision-making

## Installation Instructions
1. Ensure Python and Pygame are installed on your system.
2. Clone the repository to your local machine.
3. Run the Python script to start the game.
