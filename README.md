# 🧩 Sudoku Console Game in C++

A fully functional Sudoku puzzle game built in C++. It features a random puzzle generator, an interactive CLI to play, and a built-in solver using backtracking. Perfect for learning recursion, 2D arrays, and game logic using object-oriented C++.

---

## 📌 Features

- ✅ Random Sudoku board generation
- 🧠 Solves the board using backtracking algorithm
- 🎮 Interactive CLI-based game with input prompts
- 🧾 Row and column numbers displayed for user-friendliness
- 🚫 Prevents user from modifying pre-filled values
- 🏁 Displays final result and solution

---

## 🎮 How to Play

- Choose option **1** to start the game
- You’ll see a Sudoku puzzle with `.` as empty cells
- Input row, column, and number to place
- Enter `0` for row when you want to quit and reveal solution

---

## 🧪 Example Game Output

### 🧾 Puzzle Display

```text
    1 2 3   4 5 6   7 8 9
1 | 5 . . | . 7 . | . . 3
2 | . 3 . | 6 . . | . 9 .
3 | . . . | . . . | 7 . .
   ------+-------+------
4 | 3 . . | 5 . . | 6 . .
5 | . . 9 | . . . | 2 . .
6 | . 6 . | . . 3 | . 8 .
   ------+-------+------
7 | . . 7 | . . . | . . .
8 | . 1 . | . . 6 | . 4 .
9 | 4 . . | . 3 . | . . 5

---

