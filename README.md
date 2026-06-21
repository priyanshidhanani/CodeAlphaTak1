# Hangman Game in Python

## Project Description

This is a simple text-based Hangman game developed in Python. The player must guess a hidden word one letter at a time. The game randomly selects a word from a predefined list and gives the player a maximum of 6 incorrect attempts to guess the word.

## Features

* Random word selection using the `random` module.
* Five predefined words.
* Maximum of 6 wrong guesses.
* Displays guessed letters in their correct positions.
* Prevents duplicate guesses.
* Win and lose conditions.

## Technologies Used

* Python
* Random Module
* Lists
* Strings
* While Loop
* If-Else Statements

## Predefined Words

* python
* apple
* computer
* school
* flower

## How to Run

1. Install Python on your system.
2. Save the program as `hangman.py`.
3. Open a terminal or command prompt.
4. Navigate to the project folder.
5. Run the command:

```bash
python hangman.py
```

## Sample Output

```
===== HANGMAN GAME =====

Word: _ _ _ _ _ _
Remaining Attempts: 6

Enter a letter: s
Correct Guess!

Word: s _ _ _ _ _
Remaining Attempts: 6
```

## Game Rules

1. Guess one letter at a time.
2. If the guessed letter is correct, it will be revealed.
3. If the guessed letter is incorrect, one attempt is deducted.
4. You have only 6 incorrect attempts.
5. Guess all letters correctly before attempts run out to win.

## Learning Outcomes

* Understanding Python lists and strings.
* Using loops and conditional statements.
* Working with user input.
* Implementing basic game logic.
* Using the random module.

## Author

Developed as a beginner Python project for learning programming concepts.
