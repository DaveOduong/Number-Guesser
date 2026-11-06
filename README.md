# Number Guessing Game

## Description
A simple Python number guessing game where the computer randomly selects a number within a specified range, and the player tries to guess it correctly.

## Features
- Generates a random number using Python's `random` module.
- Allows the player to guess repeatedly until correct.
- Displays **"Too low"** when the guess is below the random number.
- Displays **"Too High"** when the guess is above the random number.
- Displays a success message when the correct number is guessed.

## How It Works
1. The `random` module generates a random number between 1 and the specified maximum.
2. The player enters a guess.
3. The program compares the guess with the randomly generated number.
4. It provides feedback depending on whether the guess is too high or too low.
5. The game continues until the correct number is entered.

## Technologies Used
- Python
- Random Module
- While Loop
- If-Else Statements
- User Input (`input()`)

## How to Run
1. Install Python.
2. Save the code as `guessing_game.py`.
3. Open a terminal in the project folder.
4. Run:

```bash
python guessing_game.py
```

## Example Output

```text
Guess a number between 1 and 10: 5
Too low
Guess a number between 1 and 10: 8
Too High
Guess a number between 1 and 10: 7
Correctly Guessed it is 7
```

## Learning Objectives
This project demonstrates the use of Python functions, random number generation, loops, conditional statements, and user input.
