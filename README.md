# Rock, Paper, Scissors Game

This is a simple browser-based Rock, Paper, Scissors game where the player competes against the computer. The game includes score tracking, dynamic updates to the user interface, and the ability to reset and play again after a game is completed.

## Features

- **Player vs. Computer Gameplay**: Play against the computer with choices of Rock, Paper, or Scissors.
- **Score Tracking**: Keep track of the player’s and computer’s scores.
- **Dynamic Messages**: Displays round results and the winner of the game.
- **Reset Option**: Reset the game to play again after a winner is declared.

## Technologies Used

- **HTML**: Structure of the web page.
- **CSS**: Styling for the game layout and elements.
- **JavaScript**: Game logic, interactivity, and dynamic updates to the UI.

## Setup and Usage

1. Clone the repository or download the project files.
   ```bash
   git clone <repository_url>
   ```
2. Open the `index.html` file in any modern web browser.

3. Play the game by selecting Rock, Paper, or Scissors from the available options.

## Game Logic

1. **Player Choice**: The player selects Rock, Paper, or Scissors.
2. **Computer Choice**: The computer randomly selects one of the three options.
3. **Winner Determination**: The game determines the winner of each round based on the rules:
   - Rock beats Scissors
   - Scissors beats Paper
   - Paper beats Rock
4. **Score Updates**: Scores are updated dynamically in the UI.
5. **Game Over**: When a player reaches a predefined score, a winner is declared, and the reset button is displayed.

## Functions Overview

### `playRound(playerChoice)`
Handles a single round of the game by comparing the player’s choice with the computer’s choice and updates the score accordingly.

### `resetGame()`
Resets the player’s and computer’s scores to 0, clears messages, hides the reset button, and shows the options for a new game.

### `getComputerChoice()`
Randomly selects Rock, Paper, or Scissors for the computer’s turn.

## User Interface Elements

- **Options Container**: Displays the Rock, Paper, and Scissors buttons for the player to choose.
- **Scoreboard**: Shows the player’s and computer’s scores dynamically.
- **Messages**: Displays round results and the winner of the game.
- **Reset But
