# Tic-Tac-Toe Game (C)

### 🎓 Context
This is a classic Tic-Tac-Toe (Jogo da Velha) developed in **C** to practice multidimensional arrays (matrices) and custom data structures using `struct`. It focuses on game state management and coordinate-based user interaction.

### 🚀 Features
* **Two-Player Mode:** Local multiplayer functionality with alternating turns between 'X' and 'O'.
* **Win/Draw Detection:** Algorithms to check for victory conditions in rows, columns, and diagonals, as well as detecting a "draw" (velha).
* **Coordinate System:** Input validation using a grid system (1-3) for a better user experience.

### 🛠️ Technical Details
* **Data Structures:** Used a `struct` to encapsulate the board matrix, promoting cleaner and more organized code.
* **Pass-by-Reference:** Extensive use of **pointers** to update the board state efficiently across different functions.
* **Input Validation:** Implementation of checks to prevent overwriting moves or entering invalid coordinates.

### 💻 How to run
1. **Compile** the code:
   ```bash
   gcc velha.c -o velha

2. **Run** the executable:
   ```bash
   ./velha
