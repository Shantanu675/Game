# Hangman Game
This is a simple Hangman game built using Python and Tkinter. The game allows players to guess letters in a word and try to figure out the word before running out of attempts.
Features

Classic Hangman game mechanics.
Graphical interface built using Tkinter.
Easy-to-use and interactive UI.
Keeps track of attempts and guessed letters.
Displays an image of the hangman as the game progresses.

# Requirements

To run this game, you need to have Python installed on your machine, along with the Tkinter library (usually bundled with Python).

Python 3.x (can be downloaded from python.org)
Tkinter (Tkinter is included with Python by default)

# Installation

Clone this repository or download the source code.

    git clone https://github.com/Shantanu675/Game.git

Navigate to the project directory:

    cd Hangman_Game

Run the game:

    python Hangman_Game.py

# How to Play

Once you run the game, a window will appear displaying the Hangman game interface.
You will be shown a word with missing letters represented by underscores (_).
Guess a letter by typing it into the text input box and pressing the "Guess" button.
If you guess a correct letter, it will appear in the correct position(s) in the word.
If you guess a wrong letter, your number of attempts decreases, and an image of a hanging stick figure is updated.
The game ends when you either guess the word correctly or run out of attempts.

# Game Rules

The game starts with a certain number of attempts (usually 6).
You must guess letters one at a time.
If you guess all the letters in the word correctly, you win!
If you run out of attempts before guessing the full word, you lose.

# Game Over Screen

When the game ends, the final result is displayed, showing either a "You Win!" or "You Lose!" message, along with the correct word.
