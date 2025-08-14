Tic Tac Toe
📌 Overview
Tic Tac Toe is a classic two-player game implemented using Java and JavaFX.
The game is played on a 3x3 grid, where players take turns marking cells with X or O.
The first player to align three marks horizontally, vertically, or diagonally wins.
If all cells are filled without a winner, the game ends in a draw.
🛠️ Tech Stack
Java – Core game logic
JavaFX – GUI for an interactive game board
🎯 Features
Two-player mode (Player X vs Player O)
Graphical user interface with clickable buttons
Win detection for all possible lines (rows, columns, diagonals)
Draw detection if the board is full
Reset game functionality without restarting the app
📂 Project Structure
TicTacToe/
│── src/
│   ├── com.tictactoe/
│   │   ├── Main.java           # JavaFX entry point
│   │   ├── TicTacToeController.java # Handles game logic and UI events
│   │   ├── Board.java          # Game board logic
│── resources/
│   ├── tic_tac_toe.fxml        # JavaFX UI layout
│   ├── style.css               # Optional styling
│── README.md
⚙️ How to Run
Clone the repository:
git clone https://github.com/yourusername/TicTacToe.git
cd TicTacToe
Open in VS Code or IntelliJ IDEA with JavaFX SDK configured.
Run Main.java to start the game.
