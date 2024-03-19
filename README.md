# Guessing-Game-Using-Python
This is python code to create a simple guessing game.
You are creating a Python program to simulate a simple guessing game. The game will have the following rules:
1.	The program will generate a random number between 1 and 50 and store it in a variable called "secret_number." For this, you will need to import randint() from the random library in python. Run the following line of code in a cell:
from random import randint
2.	The user will be given 5 attempts to guess the "secret_number."
3.	The program will use a while loop to repeatedly ask the user for their guess and provide feedback based on their input. (Remember that input() returns a string even if the user enters a number.) 
4.	First, handle the case where the user enters a non-numeric input. For this, you will need to add a try/except block. Google the syntax and under the try block, convert the guess into an int. If the entry is non-numeric, this conversion should fail and python will go to the except block. Under the except block, handle this error by printing "Invalid input! Please enter a valid number” and utilize the continue statement to allow the user to try again without reducing their remaining attempts.
5.	If the user guesses the correct number, print "Congratulations! You guessed the secret number [secret_number] correctly!" and break out of the loop.
6.	If the user's guess is too high, print "Try again! Your guess is too high. You have [attempts_left] attempts left." where "attempts_left" is the number of remaining attempts.
7.	If the user's guess is too low, print "Try again! Your guess is too low. You have [attempts_left] attempts left."
8.	If the user runs out of attempts, print "Game Over! The secret number was [secret_number]. Better luck next time!" and break out of the loop.
