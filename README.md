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


Do you want me to also **add a section for "Possible Improvements"** so your README looks even more professional? That would make it look like a GitHub project README.
