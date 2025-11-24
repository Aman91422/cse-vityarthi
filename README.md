# cse-vityarthi
Number Guessing Game

This is a simple command-line number guessing game implemented in Python. The computer selects a random integer within a defined range, and the user attempts to guess that number. The program provides hints (too high or too low) after each guess to help the user narrow down the possibilities.

The main application code is contained in cse_assignment.py.

Features

Random Number Generation: The secret number is generated randomly between 1 and 100.

User Feedback: Provides immediate feedback ("Too high!" or "Too low!") after every guess.

Guess Counter: Tracks and reports the total number of attempts taken to guess the correct number.

Input Validation: Handles non-integer input gracefully, prompting the user to enter a whole number.

Requirements

The game requires Python 3.x to run.

No external libraries are needed, as it only uses the built-in random module.

How to Run

Save the file: Ensure the cse_assignment.py file is saved on your machine.

Open your terminal/command prompt.

Navigate to the directory where you saved the file.

Execute the script using the Python interpreter:

python cse_assignment.py


Gameplay Example

When you run the script, you will see a welcome message and be prompted to enter your guess:

 Welcome to the Number Guessing Game! 
I am thinking of a number between 1 and 100.
Try to guess it!

Enter your guess: 50
Too high! ⬆ Guess lower.

Enter your guess: 25
Too low! ⬇ Guess higher.

...

Enter your guess: 37

 CONGRATULATIONS! You complete it! 🎉
The number was 37.
You took 7 guesses.


Code Structure

The game logic is encapsulated within a single function:

number_guessing_game(): Initializes the game, sets the bounds (1-100), generates the secret number, runs the main guessing loop, handles input, provides hints, and displays the final winning message.
