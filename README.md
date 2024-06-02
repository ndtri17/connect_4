# Connect Four Game

This repository hosts the code for a Connect Four game implemented in JavaScript. The game supports both two-player and single-player modes, where the single-player mode features a challenging AI bot. The game interface is user-friendly, and the interactions are intuitively designed for an engaging gameplay experience.

## Features

### Gameplay Modes
- **Two-Player Mode**: Two players can play against each other using alternating turns.
- **Single-Player Mode against AI**: Play against an AI bot designed with a simple yet effective decision-making algorithm.

### Dynamic Score Tracking
- Scores for both players are tracked and displayed in real-time.
- Separate score tracking for human vs. human and human vs. AI games.

### AI Bot
- The AI bot utilizes a minimax algorithm with alpha-beta pruning to decide on its moves, making it a competitive opponent.

### Interactive UI
- The user interface updates dynamically to show the current state of the game board and player scores.
- Interactive cells that respond to mouse hover, enhancing user experience.

## Technical Overview

### Board State Management
- The game board is represented as an array of strings, initialized to empty and updated as players make moves.

### Event Handling
- JavaScript event listeners are used to handle player interactions like mouseover, mouseout, and clicks on the game board.

### Minimax Algorithm with Alpha-Beta Pruning
- The AI's decision-making process is powered by the minimax algorithm, optimized with alpha-beta pruning to enhance performance by reducing the number of nodes evaluated.

### DOM Manipulation
- Real-time updates to the Document Object Model (DOM) to reflect changes in the game state and player scores.

## Setup and Usage

1. **Clone the repository**:
