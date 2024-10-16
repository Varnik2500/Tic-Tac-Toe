# Tic-Tac-Toe Game

This is a simple implementation of a Tic-Tac-Toe game using HTML, CSS, and JavaScript. The game can be played between two players (Player X and Player O) on the same device.

## Table of Contents
- [Features](#features)
- [How to Play](#how-to-play)
- [Files](#files)
- [How to Run](#how-to-run)
- [Game Logic](#game-logic)
- [Technologies Used](#technologies-used)

## Features
- Two-player game: Players X and O take turns.
- The game checks for winners and declares if a player has won.
- Draw scenario handling.
- Reset button to start a new game.
- Responsive and clean design with CSS.

## How to Play
1. Open the `index.html` file in your browser.
2. Players take turns clicking on the boxes to place their symbol (`X` or `O`).
3. The first player to align 3 symbols either horizontally, vertically, or diagonally wins.
4. If all boxes are filled and there is no winner, the game will declare a draw.
5. You can reset the game using the "Reset Game" or "New Game" button at any time.

## Files

- **index.html**: The main structure of the webpage.
- **style.css**: The styles and layout of the game board.
- **script.js**: The game logic and interactivity.

## How to Run
1. Clone the repository.
```
https://github.com/Varnik2500/Tic-Tac-Toe.git
```
3. Open the `index.html` file in any modern web browser (e.g., Chrome, Firefox, Edge).
4. Enjoy playing the game.

## Game Logic
- The game board consists of 9 boxes (3x3 grid).
- Players take turns to mark an empty box with either `X` or `O`.
- The game checks the board after each move for a winner based on predefined win patterns.
- The game can result in three scenarios:
  1. **Win**: If a player aligns three symbols.
  2. **Draw**: If all boxes are filled with no winner.
  3. **Reset**: Players can reset the game at any time.

## Technologies Used
- **HTML5**: To structure the game board and layout.
- **CSS3**: For styling the game board and making it visually appealing.
- **JavaScript(ES6)**: To handle the game logic, user interactions, and determine the game result.

## Future Enhancements
- Add AI functionality to allow single-player mode.
- Implement a scoreboard to track multiple games.
- Improve responsiveness for smaller devices.
