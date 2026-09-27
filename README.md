# Rock Paper Scissors Game

## Introduction

This is a simple Rock Paper Scissors game developed using Python. In this game, the user plays against the computer. The computer randomly selects one option from rock, paper, or scissor, and the user enters their choice.

The program compares both choices and determines whether the user wins, the computer wins, or the game is a tie.

The player can also choose to play multiple rounds.

## Features

* User can choose rock, paper, or scissor.
* Computer randomly selects a choice.
* The program checks whether the user's input is valid.
* The program determines the winner.
* The game displays the choices made by both the user and computer.
* The player can play again after each round.
* The game ends when the player chooses not to continue.

## Technologies Used

* Python 3
* Python Random module

No external libraries are required for this project.

## How the Game Works

The program first creates a list containing three choices:

```python
choices = ["rock", "paper", "scissor"]
```

The computer randomly selects one choice using the `random.choice()` function.

The user is then asked to enter their choice.

The program checks the user's input. If the input is not rock, paper, or scissor, it displays an invalid choice message.

If the input is valid, the program compares the user's choice with the computer's choice and determines the result.

The player is then asked whether they want to play again. If they enter "yes", a new game starts. Otherwise, the program ends.

## Game Rules

* Rock beats Scissor.
* Scissor beats Paper.
* Paper beats Rock.
* If both players choose the same option, the result is a tie.

## Project Structure

```text
Rock-Paper-Scissors/
│
├── rock_paper_scissors.py
└── README.md
```

## How to Run the Project

First, make sure Python 3 is installed on your computer.

Check the Python version using:

```bash
python --version
```

Run the program using:

```bash
python rock_paper_scissors.py
```

## Example

```text
Enter rock, paper, or scissor: rock

Your choice: rock
Computer choice: scissor

You win!

Do you want to play again? (yes/no): yes

Enter rock, paper, or scissor: paper

Your choice: paper
Computer choice: paper

It's a tie!

Do you want to play again? (yes/no): no

THANKS FOR PLAYING!
```

## Python Concepts Used

This project helped me practice some basic Python concepts, including:

* Variables
* Lists
* User input
* Conditional statements
* While loops
* String methods
* The random module
* Comparison operators
* Basic program logic

## Future Improvements

The project can be improved by adding:

* A score system to keep track of wins and losses.
* A player name.
* Different difficulty levels.
* A graphical user interface using Tkinter.
* A web version using Flask or Streamlit.
* Statistics showing the number of wins, losses, and ties.

## Author

Edakula Pranay Kumar

This project was created as a beginner Python project to practice programming concepts and conditional logic.

## License

This project is created for educational and learning purposes.
