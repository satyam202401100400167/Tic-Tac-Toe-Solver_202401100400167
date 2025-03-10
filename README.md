# Tic-Tac-Toe-Solver

### Overview

Tic-Tac-Toe is a classic two-player game where players take turns marking spaces in a 3x3 grid. This project implements a Python-based AI solver using the Minimax algorithm, ensuring the AI always makes the optimal move. The human player competes against the AI, which calculates the best possible move at each turn.

### Features

- Playable Tic-Tac-Toe game with AI opponent.

- AI makes optimal moves using the Minimax algorithm.

- Interactive command-line interface.

- Detects game outcomes (win, lose, or draw).

### How It Works

- The game board is represented using a 3x3 NumPy array.

- The human player plays as 'X' and the AI plays as 'O'.

- The AI uses the Minimax algorithm to evaluate all possible moves and determine the best move.

- The game continues until either the human player or AI wins, or the board is full (draw).

### Installation & Setup

To run the Tic-Tac-Toe solver on your local machine, follow these steps:

### Prerequisites

Ensure you have Python installed (version 3.x recommended). You will also need NumPy for array operations.

### Installation

- Clone this repository:

```
git clone https://github.com/yourusername/tic-tac-toe-solver.git
cd tic-tac-toe-solver
```

- Install required dependencies:

```
pip install numpy
```
- Run the game:

```
python tic_tac_toe.py
```

### How to Play

- The game starts with an empty 3x3 grid.

- The human player chooses a row and column index (0-2) to place 'X'.

- The AI calculates its optimal move using Minimax and places 'O'.

- The game continues until there is a winner or a draw.

- The program displays the result and exits.
