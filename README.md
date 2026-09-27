# 🎯 Number Guessing Game

## 📌 Project Description

The **Number Guessing Game** is a simple Python project for beginners. In this game, the computer randomly selects a number between **1 and 100**, and the player tries to guess the number.

After each guess, the program gives a hint:

* **Too low** – if the guessed number is smaller than the secret number.
* **Too high** – if the guessed number is larger than the secret number.
* **Correct** – if the player guesses the number successfully.

The game also counts the number of attempts taken by the player.

---

## 🎯 Objectives

* To understand basic Python programming.
* To practice `if-elif-else` statements.
* To understand `while` loops.
* To use user input.
* To generate random numbers using Python.
* To practice variables and counters.

---

## ✨ Features

* Generates a random number between 1 and 100.
* Accepts guesses from the user.
* Provides hints after every guess.
* Counts the number of attempts.
* Displays a congratulations message when the correct number is guessed.

---

## 🛠️ Technologies Used

* **Programming Language:** Python
* **Module Used:** `random`

---

## 📂 Project Structure

```text
Number_Guessing_Game/
│
├── main.py
└── README.md
```

### `main.py`

Contains the complete game program.

### `README.md`

Contains information about the project, its features, and how to run it.

---

## ▶️ How to Run the Project

### Step 1: Install Python

Make sure Python is installed on your computer.

Check the Python version using:

```bash
python --version
```

or:

```bash
python3 --version
```

### Step 2: Open the Project

Open the `Number_Guessing_Game` folder in VS Code or any Python editor.

### Step 3: Run the Program

Use:

```bash
python main.py
```

or on some systems:

```bash
python3 main.py
```

---

## 🎮 How to Play

1. Start the program.
2. The computer generates a random number between 1 and 100.
3. Enter your guess.
4. The program tells you whether your guess is too high or too low.
5. Continue guessing until you find the correct number.
6. The program displays the total number of attempts.

---

## 💻 Example

```text
🎯 Number Guessing Game
I have selected a number between 1 and 100.

Enter your guess: 50
Too high! Try again.

Enter your guess: 25
Too low! Try again.

Enter your guess: 32
🎉 Congratulations!
You guessed the correct number.
Number of attempts: 3
```

---

## 🧠 Python Concepts Used

| Concept            | Purpose                  |
| ------------------ | ------------------------ |
| Variables          | Store game data          |
| `input()`          | Get the user's guess     |
| `random.randint()` | Generate a random number |
| `while` loop       | Continue the game        |
| `if-elif-else`     | Compare the guess        |
| `break`            | End the game             |
| Counter            | Count attempts           |

---

## 🚀 Future Improvements

The project can be improved by adding:

* Difficulty levels
* Limited number of attempts
* Score system
* Replay option
* High-score tracking
* Input validation
* GUI using Tkinter

---

## 👨‍💻 Author

**Your Name**

This project was created as a beginner Python project to practice basic programming concepts.
