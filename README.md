# 🎯 Sudoku Solver – C++ Implementation  

Solve **9x9 Sudoku puzzles** efficiently using **Backtracking and Constraint Propagation**! This C++ solver finds valid solutions while ensuring **optimal performance**. 🚀  

---

## 📌 Features  
✅ **Backtracking Algorithm** – Efficiently explores possible solutions using depth-first search.  
✅ **Constraint Propagation** – Reduces search space for faster solving.  
✅ **Flexible Input** – Accepts puzzles from standard input or a file.  
✅ **Optimized Performance** – Designed for speed and efficiency.  
✅ **Clear Output** – Displays the solved grid in a user-friendly format.  

---

## ⚡ How It Works  
1. Reads the **9x9 Sudoku grid** (empty cells as `0`).  
2. Applies **backtracking** with **constraint propagation** to find a valid solution.  
3. Prints the **solved Sudoku** in a structured format.  

---

## 🛠️ Installation & Usage  

### 🔹 Clone the Repository  
```sh
git clone https://github.com/deeplukhi/sudoku-solver.git
cd sudoku-solver
```

### 🔹 Compile the Code  
```sh
g++ sudoku_solver.cpp -o sudoku_solver
```

### 🔹 Run the Solver  
```sh
./sudoku_solver < input.txt
```
or manually enter the puzzle when prompted.  

---

## 📜 Example  

### 🔹 Input  
```
5 3 0  0 7 0  0 0 0  
6 0 0  1 9 5  0 0 0  
0 9 8  0 0 0  0 6 0  

8 0 0  0 6 0  0 0 3  
4 0 0  8 0 3  0 0 1  
7 0 0  0 2 0  0 0 6  

0 6 0  0 0 0  2 8 0  
0 0 0  4 1 9  0 0 5  
0 0 0  0 8 0  0 7 9  
```

### 🔹 Output  
```
5 3 4  6 7 8  9 1 2  
6 7 2  1 9 5  3 4 8  
1 9 8  3 4 2  5 6 7  

8 5 9  7 6 1  4 2 3  
4 2 6  8 5 3  7 9 1  
7 1 3  9 2 4  8 5 6  

9 6 1  5 3 7  2 8 4  
2 8 7  4 1 9  6 3 5  
3 4 5  2 8 6  1 7 9  
```

---

## 🧑‍💻 Contributing  
Contributions are welcome! Feel free to **optimize the solver** or **add new features**.  

1. **Fork** the repo  
2. **Create a new branch** (`git checkout -b feature-branch`)  
3. **Commit changes** (`git commit -m "Improved algorithm"`)  
4. **Push to your branch** (`git push origin feature-branch`)  
5. **Create a Pull Request**  

---

## 📜 License  
This project is **open-source** under the **MIT License**.  

📌 **Star this repo** ⭐ if you find it useful! 🚀
