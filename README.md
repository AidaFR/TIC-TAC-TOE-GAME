# Tic Tac Toe - Space Edition

Welcome to **Tic Tac Toe - Space Edition**! This project is a space-themed Tic Tac Toe game with a unique twist: animated **rocket explosions** and **confetti** celebrate each game's outcome.

This GUI application is built using **Python's Tkinter** library, creating an interactive board with a custom space-themed background and AI-powered opponent.

## Features

-   **Single Player Mode**: Play against a computer opponent with a decision tree AI.
-   **Space-Themed Graphics**: A custom starry sky, planets, and rockets decorate the background.
-   **Interactive Animations**: Confetti and rocket explosion animations make winning or losing exciting.
- # Gameplay Overview

### Board Setup

-   A **3x3 grid** is used for the game board, where players take turns placing their symbols (`O` for the player and `X` for the AI).

### Winning Conditions

-   The first player to align three symbols in a row, column, or diagonal wins.
-   If all spaces are filled with no winner, the game ends in a draw

## Installation & Requirements

-   **Python 3.x**
-   **Tkinter library** (comes pre-installed with Python)

# Main Functions and Classes

## 1. `TicTacToe` Class

This class creates the game window, initializes the board, handles player moves, and integrates the game AI.

### Key Methods

-   **`__init__`**: Initializes the GUI, sets up the canvas, and calls functions to draw the space background and the game board.
-   **`draw_space_background`**: Draws the animated space background, including stars, planets, and rockets.
-   **`create_buttons`**: Sets up the game buttons on the 3x3 grid.
-   **`on_button_click`**: Handles player's move and checks for game completion.
-   **`computer_move`**: Determines the computer's best move using a decision tree.
-   **`end_game`**: Checks the winner and triggers animations depending on the outcome.
-   **`show_confetti`**: Displays confetti animation when the player wins.
-   **`explode_rocket`**: Simulates a rocket explosion animation if the AI wins.
-   **`reset_board`**: Resets the board for a new game.

## 2. AI Decision Tree

The **AI uses a decision tree** to determine optimal moves:

-   **`build_decision_tree`**: Generates possible game states from the current board.
-   **`evaluate_tree`**: Evaluates scores for possible game outcomes using minimax.
-   **`best_move_from_tree`**: Chooses the best move based on evaluated scores, with a random chance to add unpredictability.

# Game Instructions

1.  **Run the game** using `python filename.py`.
2.  The player uses **O** and the computer uses **X**.
3.  Click a cell on the board to place your symbol.
4.  The computer will respond with its move.
5.  Enjoy the **animated results**: confetti if you win or a rocket explosion if you lose!


