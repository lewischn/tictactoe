# Tic-Tac-Toe Game

A classic Tic-Tac-Toe game built with React, featuring move history, time travel, and winning line highlighting.

## Features

- **Two-Player Gameplay**: Play X and O alternately
- **Winner Detection**: Automatically detects and highlights winning combinations
- **Move History**: View all moves with row and column coordinates
- **Time Travel**: Jump back to any previous move in the game
- **Winning Line Highlight**: Winning squares are highlighted in yellow
- **Current Move Indicator**: Shows which move you're currently viewing

## Installation

1. Clone the repository:
git clone https://github.com/lewischn/tic-tac-toe.git
cd tic-tac-toe

2. Install dependencies:
npm install

3. Start the development server:
npm start

4. Open http://localhost:3000 in your browser

## How to Play

1. Players take turns clicking on empty squares
2. X always goes first
3. The first player to get 3 marks in a row (horizontally, vertically, or diagonally) wins
4. Use the move history on the right to jump back to any previous state
5. The current move is displayed, and you can click any previous move to go back in time

## Game Features

### Move History
Each move is recorded with its position in (row, column) format. Click any move in the history to return to that game state.

### Winning Detection
The game automatically detects when a player has won and:
- Displays the winner
- Highlights the winning line in yellow
- Prevents further moves

### Time Travel
You can go back to any previous move, and the game will restore the board to that exact state. Continue playing from any point in history!

## Technologies Used

- React (with Hooks)
- JavaScript 
- CSS

## Project Structure

- **tic-tac-toe/**
  - **src/**
    - **App.js** – Main game component with all logic  
    - **App.css** – Styling for the game board  
    - **index.js** – Entry point  
  - **public/**  
  - **package.json**

  ## Component Breakdown

- **Game**: Main component managing game state and history
- **Board**: Renders the 3x3 grid of squares
- **Square**: Individual clickable square component

## License

MIT License

---

Enjoy playing!