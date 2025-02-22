# Guessing-the-Number
import random

print("Welcome to the game .This is a game of guessing the number .")
print("You have only 1 Chances to Guess the number")
print("            GOOD LUCK 👍          ")

guess_number=random.randrange(1)

my_guess =int(input("Enter your number : "))

if my_guess == guess_number:
    print(f"the number you entered is right ! congratulations")

elif guess_number>=my_guess :
    print(f"the number you Entered  is not correct ")
    print(f"the correct number was {guess_number}")

elif guess_number<=my_guess :
    print(f"the number you entered is not correct ")
    print(f"the correct number was {guess_number}")

else:
    ("Thank you for participating in the game.")
