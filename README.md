# file: guess_number.py
import random

def guess_number():
    number = random.randint(1, 100)
    attempts = 0

    print("🎲 I have chosen a number between 1 and 100. Try to guess it!")

    while True :
        try:
            guess = int(input("Your guess: "))
            attempts += 1
            if guess < number:
                print("🔼 My number is higher!")
            elif guess > number:
                print("🔽 My number is lower!")
            else:
                print(f"✅ Correct! The number was {number}.")
                print(f"Attempts: {attempts}")
                break
        except ValueError:
            print("Please enter a valid number.")

if __name__ == "__main__":
    guess_number()

