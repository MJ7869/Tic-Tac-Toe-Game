# Tic-Tac-Toe-Game

This is a simple Python implementation of the classic Tic-Tac-Toe game. The game is played on a 3x3 grid where two players take turns marking the spaces in the grid. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row wins the game. If all nine squares are filled and no player has three marks in a row, the game is a draw.

**Features**

- **Two-Player Mode:** The game allows two players to play against each other, taking turns to place their marks (X or O) on the grid.

- **Winner Detection:** The game automatically detects a winner when three marks align horizontally, vertically, or diagonally.

- **Draw Detection:** If all spaces are filled and no player has won, the game declares a draw.

- **Input Timeout:** Players have a limited time (10 seconds) to make their move. If the time runs out, the game ends.

**How to Play**

- **Run the Game:** Start the game by running the Python script.

- **Input:** Players will be prompted to enter a position (0-8) corresponding to the grid positions.

- **Grid Positions:**

                          0 | 1 | 2
                          ---------
                          3 | 4 | 5
                          ---------
                          6 | 7 | 8
  
- **Winning the Game:** The first player to align three marks (X or O) in a row (horizontally, vertically, or diagonally) wins.
  
- **Draw:** If all spaces are filled and no player has aligned three marks, the game ends in a draw
