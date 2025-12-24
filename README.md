# 🧩 Sudoku Solver (Backtracking Algorithm)

## 📌 Project Overview
This project implements an **automatic Sudoku Solver** using the **backtracking algorithm**.
The program takes an **unsolved 9×9 Sudoku grid** as input (with 0 representing empty cells)
and fills in the missing numbers while following Sudoku rules.

---

## ✨ Features
- Solves standard 9×9 Sudoku puzzles
- Uses **backtracking technique**
- Automatically fills missing values
- Displays both unsolved and solved grids
- Simple and easy-to-understand logic

---

## 🛠️ Technologies Used
- **Programming Language:** Python  
- **Algorithm:** Backtracking  

---

## 📂 Files Included
- `sudoku_solver.py` – Main Sudoku solver program  
- `README.md` – Project documentation  

---

## ▶️ How to Run the Program
1. Make sure Python is installed on your system.
2. Save the program as `sudoku_solver.py`.
3. Open a terminal or command prompt.
4. Run the program using:
   ```
   python sudoku_solver.py
   ```
5. The unsolved and solved Sudoku grids will be displayed.

---

## 🧠 Algorithm Description
1. Find an empty cell in the grid.
2. Try numbers from 1 to 9.
3. Check if the number is valid in the current row, column, and 3×3 box.
4. Place the number and recursively attempt to solve the rest of the grid.
5. Backtrack if no valid number can be placed.

---

## 🧪 Sample Input
```
[5, 3, 0, 0, 7, 0, 0, 0, 0]
[6, 0, 0, 1, 9, 5, 0, 0, 0]
...
```

## ✅ Sample Output
```
[5, 3, 4, 6, 7, 8, 9, 1, 2]
[6, 7, 2, 1, 9, 5, 3, 4, 8]
...
```

---

## 🎓 Academic Use
This project is suitable for:
- Data Structures & Algorithms labs
- Python programming assignments
- Demonstrating recursion and backtracking
- Mini projects

---

## 👩‍💻 Author
Developed as part of an academic assignment.
