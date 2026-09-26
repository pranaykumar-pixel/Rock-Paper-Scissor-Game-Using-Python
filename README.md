# Rock Paper Scissors Game

## Introduction

This is a simple Rock Paper Scissors game created using Python. The game allows the user to choose between rock, paper, and scissor. The computer randomly selects one of the three choices, and the program compares both choices to determine the winner.

This project was created as a beginner-level Python project to practice basic programming concepts such as user input, conditional statements, lists, and random selection.

## How the Game Works

The game follows the standard rules of Rock Paper Scissors:

* Rock beats Scissor
* Scissor beats Paper
* Paper beats Rock
* If both the user and computer choose the same option, the game is a tie.

The computer's choice is generated randomly using Python's `random` module.

## Tools and Technologies Used

* Python
* Python `random` module
* Conditional statements (`if`, `elif`, `else`)
* Lists
* User input
* String formatting using f-strings

## Features

* User can choose rock, paper, or scissor.
* Computer makes a random choice.
* The program checks whether the user's input is valid.
* The user's and computer's choices are displayed.
* The program determines whether the user wins, loses, or gets a tie.
* Simple command-line interface.

## Concepts Practiced

This project helped me practice the following Python concepts:

1. Importing and using a Python module.
2. Creating and using lists.
3. Taking input from the user.
4. Using `random.choice()` to select a random value.
5. Using `if`, `elif`, and `else` statements.
6. Using logical operators such as `and` and `or`.
7. Using f-strings to display output.
8. Handling invalid user input.

## Example Output

```text
enter rock, paper, and scissor : rock
your choice : rock
computer choice : paper
computer wins
```

Another possible result:

```text
enter rock, paper, and scissor : scissor
your choice : scissor
computer choice : paper
you wins
```

If both choices are the same:

```text
enter rock, paper, and scissor : paper
your choice : paper
computer choice : paper
it's a tie
```

## Result

The Rock Paper Scissors game successfully takes the user's choice, generates a random choice for the computer, compares both choices, and displays the result.

This project demonstrates how basic Python programming concepts can be combined to create a simple interactive game.

## Future Improvements

The project can be improved by adding:

* Multiple rounds.
* A score system for the user and computer.
* An option to play again without restarting the program.
* Better input handling for uppercase and lowercase letters.
* A graphical user interface.
* A more user-friendly menu.

## Conclusion

This project is a basic implementation of the Rock Paper Scissors game using Python. It was useful for understanding how conditional logic, user input, lists, and random values work together in a small programming project.
