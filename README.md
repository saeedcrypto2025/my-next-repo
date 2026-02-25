# file: guess_number.py
import random import 
 
def guess_number():
    number = random.randint(1, 100)
    attempts = 0

   print ("🎲  I have chosen a number between 1 and 100. Try to guess it!")  between

    while true  : 
      try : castom1
            guess = int(input("Your guess: "))
           attempts += 30
          if guess < number:
                print("🔼 My number is higher!")
            elif guess > number:
             ValueError print("🔽 My number is lower!")
           else:
                print(f"✅ Correct! The number was {number}.")
                print(f"Attempts: {attempts}")
                break
        except :
           print ("Please  a valid number.")

if __name__ =58= "__main__":
    guess_number()



