# CodSoft
----------
# TASK 1 — Guess The Number Game 🎯

## 📌 Description

This is a simple **Guess The Number** game written in **C++**.
The program randomly generates a number between **1 and 100**, and the player must guess it within a limited number of attempts depending on the chosen difficulty level.

The game gives hints after each wrong guess to help the player — whether the secret number is **greater** or **smaller** than the guessed number.

Players can choose from **3 difficulty levels** or exit the game.

---

## 🚀 Features

* **Random number generation** every round.
* **Multiple difficulty levels**:

  * Easy → 10 guesses
  * Medium → 7 guesses
  * Hard → 5 guesses
* Hints after wrong guesses.
* Option to exit anytime.

---

## 📂 How to Run

1. **Compile the program**:

   ```bash
   g++ task1.cpp -o task1
   ```
2. **Run the program**:

   ```bash
   ./task1
   ```

---

## 📋 Example Gameplay

**Run Example**

```
            Welcome to GuessTheNumber game!
You have to guess a number between 1 and 100. You'll have limited choices based on the level you choose. Good Luck!

Enter the difficulty level: 
1 for easy!    2 for medium!    3 for difficult!    0 for ending the game!

Enter the number: 1

You have 10 choices for finding the secret number between 1 and 100.

Enter the number: 50
Nope, 50 is not the right number
The secret number is smaller than the number you have chosen
9 choices left.

Enter the number: 25
Nope, 25 is not the right number
The secret number is greater than the number you have chosen
8 choices left.

Enter the number: 30
Well played! You won, 30 is the secret number
             Thanks for playing....
Play the game again with us!!
```

---

## 🎮 Difficulty Levels

| Level     | Number of Attempts | Command Input |
| --------- | ------------------ | ------------- |
| Easy      | 10                 | 1             |
| Medium    | 7                  | 2             |
| Hard      | 5                  | 3             |
| Exit Game | —                  | 0             |

---

## 🛠 Code Concepts Used

* Random number generation with `rand()` and `srand()`.
* Loops for repeated guessing.
* Conditional statements for game logic.
* User input handling.

---
# TASK 2 — Simple Calculator 🧮

## 📌 Description

This is a **basic calculator program** written in **C++**.
It takes a mathematical operator (**+**, **-**, **\***, **/**) and two numbers from the user, then performs the selected operation and displays the result.

If the user enters an invalid operator, the program displays an **error message**.

---

## 🚀 Features

* Supports **addition**, **subtraction**, **multiplication**, and **division**.
* Simple and easy-to-use command-line interface.
* Handles invalid operator inputs gracefully.

---

## 📂 How to Run

1. **Compile the program**:

   ```bash
   g++ task2.cpp -o task2
   ```
2. **Run the program**:

   ```bash
   ./task2
   ```

---

## 📋 Example Gameplay

**Run Example 1** (Addition)

```
Enter operator: +, -, *, /: +
Enter two operands: 5 3
5 + 3 = 8
```

**Run Example 2** (Division)

```
Enter operator: +, -, *, /: /
Enter two operands: 10 4
10 / 4 = 2.5
```

**Run Example 3** (Invalid Operator)

```
Enter operator: +, -, *, /: %
Enter two operands: 10 3
Error! operator is not correct
```

---

## 🎯 Operators Supported

| Operator | Operation      |
| -------- | -------------- |
| `+`      | Addition       |
| `-`      | Subtraction    |
| `*`      | Multiplication |
| `/`      | Division       |

---

## 🛠 Code Concepts Used

* **Switch case** for operator selection.
* **User input handling** with `cin`.
* **Basic arithmetic operations** in C++.

---
# TASK 3 — Tic-Tac-Toe Game ❌⭕

## 📌 Description

This is a **Tic-Tac-Toe** game implemented in **C++** using **Object-Oriented Programming (OOP)** principles.
Two players take turns marking the spaces in a **3×3 grid** with their symbols (`X` or `O`). The player who succeeds in placing three of their symbols in a **horizontal**, **vertical**, or **diagonal** row wins.
If all spaces are filled without a winner, the game ends in a **draw**.

---

## 🚀 Features

* **Two-player mode** (Player X vs Player O).
* Checks for **valid moves** before placing a symbol.
* Declares **winner** immediately upon a winning move.
* Detects **draw** when all cells are filled.
* Uses **OOP concepts**:

  * **Classes** (`Player`, `Board`, `TicTacToe`)
  * **Encapsulation** for data safety.
  * **Constructors** for initialization.

---

## 📂 How to Run

1. **Compile the program**:

   ```bash
   g++ task3.cpp -o task3
   ```
2. **Run the program**:

   ```bash
   ./task3
   ```

---

## 📋 Example Gameplay

```
Welcome to Tic-Tac-Toe!
-------------
|   |   |   | 
-------------
|   |   |   | 
-------------
|   |   |   | 
-------------
Player X (X), enter row (1-3) and column (1-3): 1 1
-------------
| X |   |   | 
-------------
|   |   |   | 
-------------
|   |   |   | 
-------------
Player O (O), enter row (1-3) and column (1-3): 1 2
...
Player X wins!
```

---

## 🎯 Winning Conditions

A player wins if they get **three in a row**:

* **Horizontal** → Same row.
* **Vertical** → Same column.
* **Diagonal** → Either main diagonal or anti-diagonal.

---

## 🛠 Code Structure

### **Class: Player**

* Stores player **symbol** (`X`/`O`) and **name**.
* Provides getters for symbol and name.

### **Class: Board**

* Maintains a **3×3 grid**.
* Handles move validation and updates.
* Checks for **win conditions**.
* Tracks the **number of filled cells**.

### **Class: TicTacToe**

* Controls the game flow.
* Manages turns between players.
* Detects win/draw conditions.

---


