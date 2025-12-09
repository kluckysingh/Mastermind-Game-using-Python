# Mastermind-Game-using-Python
# Number Guessing Game (Mastermind Style)

This project is a simple Python-based number guessing game where the player tries to guess a randomly generated 4-digit number. After each guess, the program provides hints about how many digits the player got correct **in the correct position**.



## 🎯 How the Game Works

1. The computer randomly selects a **4-digit number** between **1000 and 9999**.
2. The player makes a guess.
3. The program checks:

   * How many digits match **in the correct position**.
   * Which digits are correct (shown in a pattern like `['5', 'X', '3', 'X']`).
4. The game continues until the player correctly guesses the number.
5. The program then displays how many attempts the player took.



## 🧠 Key Features

* Random 4-digit number generation
* Digit-by-digit comparison
* Feedback after every guess
* Tracks number of attempts
* Beginner-friendly logic and structure



## 📝 Code Explanation Summary

### **count = 0**

Used to track the number of digits guessed correctly **in the correct position**.

### **correct = ['X'] * 4**

A list used to visually show which digit positions are correct. `'X'` means incorrect; correct digits replace `'X'`.


## ▶️ How to Run the Game

1. Install Python 3.
2. Save the game code in a `.py` file (e.g., `guess_game.py`).
3. Run the script in terminal or VS Code:

   ```bash
   python guess_game.py
   ```
4. Start guessing the number!



## 📌 Example Gameplay

Guess the 4 digit number: 5023
Not quite the number. But you did get 1 digit(s) correct!
Correct digits in correct positions: ['5', 'X', 'X', 'X']

Enter your next 4-digit guess: 5738
You've become a Mastermind!
It took you only 2 tries.



## ❤️ Contribution

If you'd like to improve the game (GUI, hints, scoring, etc.), feel free to modify and extend it.
