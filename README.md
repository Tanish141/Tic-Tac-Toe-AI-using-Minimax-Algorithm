## 🎮 Tic-Tac-Toe Game with AI

This project implements a command-line **Tic-Tac-Toe game with an intelligent AI** opponent using the Minimax algorithm. The AI plays optimally, making it a challenging opponent to beat!

---

## 🚀 Features
- Two-player Interaction: Human vs. AI gameplay.
- AI with Minimax Algorithm: Ensures the AI makes optimal moves.
- Dynamic Board Display: Displays the game board after every turn.
- Validation: Handles invalid inputs and prevents overwriting moves.
- Game Outcomes: Detects win, draw, and ongoing game states.

---

## 🛠️ How It Works
- **Game Flow:**
- Board Initialization: A 3x3 board is represented as a list of 9 elements.

- Player Moves:
- The player chooses a move by entering a number (1-9).
- Input is validated to ensure it's within range and the cell is unoccupied.

- AI Moves:
- The AI calculates its best move using the Minimax algorithm, considering all possible outcomes.

- Winning Condition:
- Rows, columns, or diagonals are checked for three identical symbols ('X' or 'O').

- Game End:
-The game announces the winner or a draw if the board is full.

---

## 🛠️ Technologies Used
- Python 🐍: Core programming language.
- Minimax Algorithm: For AI decision-making.

---

## 📂 Code Structure

- Board Management:
- The board is displayed dynamically after every move.
- Input validation prevents invalid moves.

- Minimax Algorithm:
- Recursively evaluates all possible moves.
- Maximizes AI's chances of winning while minimizing the player's chances.

- Game Logic:
- Detects win conditions and ensures smooth gameplay.

---

## 🚀 How to Play

Run the Game:

python tic_tac_toe.py

Make Your Move:

Enter a number (1-9) corresponding to the board position:

1 | 2 | 3

---+---+---
4 | 5 | 6
---+---+---
7 | 8 | 9



Game Outcome:

The game ends when:

A player wins (3 consecutive symbols in a row, column, or diagonal).

The board is full (resulting in a draw).

---

## 📊 Example Gameplay

Initial Board:

  |   |  
---------
  |   |  
---------
  |   |  

Player Move:

  X |   |  
---------
    |   |  
---------
    |   |  

AI Move:

  X |   |  O
---------
    |   |  
---------
    |   |  

---

## 🏅 Key Features of the AI

Optimal Decision-Making: The AI uses the Minimax algorithm to explore all possible game outcomes.

Handles All Cases: Ensures the AI never loses unless forced.

---

## 🤝 Contributions

Feel free to fork the repository, create a feature branch, and submit a pull request. Contributions are always welcome! 🌟

---

## 📧 Contact

For any questions or suggestions, reach out:

Email: mrtanish14@gmail.com

GitHub: [Your GitHub Profile](https://github.com/Tanish141)

---

**🎉 Happy Playing!**
