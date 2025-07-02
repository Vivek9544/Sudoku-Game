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

### 🧾 Main Menu
Sudoku Game Menu:

Play Game

Exit
Enter choice:

yaml
Copy
Edit

---

### 🧩 Puzzle Display
Copy
Edit
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

yaml
Copy
Edit

---

### 🎯 User Input Example
Enter row (1-9) or 0 to view solution and quit: 1
Enter column (1-9): 2
Enter number to place (1-9): 8
Correct move.

yaml
Copy
Edit

---

### 🏁 Puzzle Completed or Solved
Congratulations! You have completed the puzzle correctly!
Final Board:

mathematica
Copy
Edit

### ✅ Full Grid (Real Sudoku Solution Example)
Copy
Edit
1 2 3   4 5 6   7 8 9 
1 | 5 8 6 | 9 7 2 | 4 1 3
2 | 7 3 4 | 6 1 8 | 5 9 2
3 | 9 2 1 | 3 5 4 | 7 6 8
------+-------+------
4 | 3 9 2 | 5 4 1 | 6 7 8
5 | 6 5 9 | 8 2 7 | 2 3 1
6 | 1 6 8 | 7 9 3 | 5 8 4
------+-------+------
7 | 8 4 7 | 1 6 5 | 3 2 9
8 | 2 1 5 | 4 8 6 | 9 4 7
9 | 4 7 3 | 2 3 9 | 1 5 6

yaml
Copy
Edit
