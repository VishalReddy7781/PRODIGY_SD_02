# PRODIGY_SD_02

Build a program that generates a random number and challenges the user to guess it. The program should prompt the user to input their guess, compare it to the generated number, and provide feedback if the guess is too high or too low. It should continue until the user correctly guesses the number and then display the number of attempts it took to win the game

Explanition:Initialize Random Number Generator:

srand(time(0)) seeds the random number generator with the current time.
rand() % 100 + 1 generates a random number between 1 and 100.
Prompt the User:

The program prompts the user to guess the number and reads their input.
Compare Guess to Random Number:

The program compares the user's guess to the generated random number.
If the guess is too high or too low, it provides feedback and prompts the user to guess again.
Loop Until Correct Guess:

The program continues to prompt the user until the correct number is guessed.
It keeps track of the number of attempts.
Congratulate the User:

When the user guesses correctly, the program congratulates them and displays the number of attempts it took to win the game.
