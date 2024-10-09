# 8-Queens Puzzle Game

## Overview
This project is an interactive implementation of the **8-Queens Puzzle**, a classic chess-based problem, built using **HTML**, **CSS**, and **JavaScript**. The objective of the game is for players to place 8 queens on an 8x8 chessboard such that no two queens threaten each other. This means that no two queens can share the same row, column, or diagonal.

### Features:
1. **Interactive Chessboard**: Users can click on the chessboard to place or remove queens.
2. **Conflict Detection**: The system alerts the player when they try to place a queen in an invalid position (i.e., in the same row, column, or diagonal as another queen).
3. **Invalid Move Highlight**: When an invalid move is made, the cell is highlighted in red, indicating a conflict.
4. **Queen Removal**: Players can remove queens by clicking on the already placed queen.
5. **Win Detection**: Once all 8 queens are placed correctly without conflicts, a "You Win!" message is displayed.
6. **Dynamic Queen Size Adjustment**: The queen icons are dynamically resized for better visual representation.
7. **No Reset of Previous Invalid Moves**: Invalid moves remain highlighted in red until a queen is removed, ensuring clarity in the game.

## How to Play:
1. Click on any empty cell on the chessboard to place a queen.
2. If the move is valid, a queen will be placed, and the game will continue.
3. If the move is invalid (i.e., the cell conflicts with an existing queen in the same row, column, or diagonal), the cell will turn red.
4. To remove a queen, click on the queen again.
5. When all 8 queens are placed correctly, a "You Win!" message will be displayed.
   
## Project Structure:
- **HTML**: Defines the structure of the chessboard and the layout of the game.
- **CSS**: Styles the chessboard, including alternating cell colors, queen images, and invalid move highlighting.
- **JavaScript**: Implements the game logic, including queen placement, conflict detection, and win conditions.

## Future Enhancements:
- Adding a move counter or timer to challenge players to solve the puzzle more efficiently.
- Integrating sound effects for valid/invalid moves and for winning the game.
- Adding an "Undo" button to remove the last placed queen.

## Getting Started:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/8-queens-puzzle.git
   ```

2. **Open the `index.html` file** in your browser to play the game locally.

## Screenshots:


## License:


