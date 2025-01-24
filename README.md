# Tic-Tac-Toe Game (Human vs AI)

This is a Tic-Tac-Toe game implemented in React.

![Tic-Tac-Toe Animation](asset/tictactoe-react.gif)


## Overview
This is a simple Tic-Tac-Toe game implemented using React, where a user can play against an AI opponent or play with another human. The AI makes moves using the **Minimax** algorithm to calculate the best possible move.

## Features
- **Human vs Human**: Allows two players to play against each other on the same device.
- **Human vs AI**: A player can challenge the AI, which will use the Minimax algorithm to make optimal moves.
- **Game Status**: Displays the current game status (in progress, winner, or draw).
- **Interactive UI**: Clickable squares that update the game state.

## Libraries Used
- **React**: JavaScript library for building the user interface.
- **Material UI**: Provides UI components like buttons and button groups for a better user interface experience.

## Game Logic
- **Minimax Algorithm**: Used by the AI to calculate the best move by simulating possible future game states.
- **Game States**: Tracks the current state of the board, the player's turns, and the game result.
- **Winning Conditions**: The game checks if a player has won or if the game ends in a draw by verifying specific lines on the board.

## Components
- **Board Component**: Contains the state of the game and renders the 3x3 grid. Handles user clicks and triggers AI moves.
- **Square Component**: Represents each individual square on the board, which can be clicked to make a move.

## Main Functions
- `handleClick(i)`: Handles user clicks, updating the board with the current player's symbol and triggering AI moves if it's the AI's turn.
- `minimax(newBoard, player)`: The AI's decision-making function using the Minimax algorithm to choose the best move.
- `calculateWinner(squares, player)`: Checks if a player has won by analyzing the board.

## How to Run
1. Clone the repository.
2. Run the following commands:
   ```bash
   npm install
   npm start
