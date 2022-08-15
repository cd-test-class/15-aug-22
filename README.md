# Pair programming club - 15th August 2022

Choose a first driver, and switch roles approximately every 10 minutes.

## Task

In the file `guess.py`, implement a game of "Guess the number". At a minimum, your program will need to:

1. Generate a random number within a range of your choice (for instance, between 1 and 10).
2. Ask the user to type in a number as a first guess.
3. Tell the user whether their guess is too high, too low, or correct.
4. Continue asking for guesses until the user finds the correct number.

### Tips:

- Discuss your coding approach with your partner as you get started, before even starting to write code. Do you want to write a simple script? Do you want to write functions, classes? What is the general structure and logic you will need?

- The function `input()` can be used to ask the user to type in something in the console. Here is an example program which displays the user's name -- try to run it:

```py
name = input('What is your name? ')
print('Hello, ' + name + '!')
```

Note that `input()` returns a `str` (a string of characters); if you wish to handle the result as a number, you will need to convert it yourself, using e.g. `int()` or `float()`.

## Extra credit

Here are a few ideas for further exercises:

- Ask the user to choose a difficulty before starting the game: "easy", "medium", "hard", each corresponding to a larger and larger range of numbers within which to guess.
- Give the user a useful error message and continue the game if what they type is not a number, or if it's outside the range.
- Give the user more detailed indications of how far they are from the target number.
- Write a bot which will play your game.
