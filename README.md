# 🎮 Tic Tac Toe - CLI Java Edition

A classic **Tic Tac Toe** game built using Java for the command line. Two players take turns to place their marks (X and O) on a 3×3 grid. The first to align three marks horizontally, vertically, or diagonally wins!

## 🚀 Features

- Fully playable in the command-line interface
- Two-player mode with alternating turns
- Input validation for moves
- Victory detection across all winning patterns
- Simple and intuitive board rendering

## 📦 How to Run

Make sure you have Java installed. Then compile and run using:

```bash
javac TicTacToe.java
java TicTacToe
```

## 🎮 Gameplay Instructions

1. The board is a 3x3 grid indexed with row and column values (0 to 2).
2. Players take turns entering the row and column numbers where they'd like to place their mark.
3. If the position is already occupied, it's considered an invalid move and skipped.
4. The game checks for a winner after every move starting from move 4.
5. It displays the winner or continues until a draw.

## 🛠️ Code Highlights

- Game board is represented as a 2D character array.
- `drawboard(char[][])` function renders the board after each move.
- Alternating turns are handled using a ternary operator: `Player = Player=='X'?'O':'X';`
- Winning conditions checked across rows, columns, and diagonals.

## 👨‍💻 Author

Developed by T S BHUVANESHWAR as part of a hands-on Java learning journey, blending logic, user interaction, and gameplay structure.

## 📌 Future Improvements

- Add input boundary checks to prevent out-of-range exceptions
- Enhance invalid move handling (currently skips a turn)
- Include draw detection when all cells are filled
- Refactor repeated winning condition code

## 🧠 Learning Outcomes

- Practiced use of arrays, loops, conditionals, and user input in Java
- Explored control flow and basic game logic
- Strengthened understanding of CLI-based application design


