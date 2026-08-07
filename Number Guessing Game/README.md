# Number Guessing Game 🔢

A simple Python game where the computer randomly selects a number between 1 and 100, and the user tries to guess it.

## Features

* Generates a random number between 1 and 100
* Allows the user to make multiple guesses
* Gives feedback if the guess is too high or too low
* Handles invalid inputs
* Ends when the correct number is guessed

## Concepts Used

* Python `while` loop
* `if-elif-else` conditions
* User input using `input()`
* Random number generation using the `random` module
* Exception handling using `try-except`
* `ValueError`
* Variables and formatted strings

## How to Run

1. Make sure Python is installed on your system.
2. Run the program using:

```bash
python number_guessing.py
```

3. Enter a number between 1 and 100.
4. Keep guessing until you find the correct number.

## Example Output

```text
Guess the number between 1 and 100: 50
Too high!

Guess the number between 1 and 100: 25
Too low!

Guess the number between 1 and 100: 37
Congratulations! You guessed the number correctly.
```
