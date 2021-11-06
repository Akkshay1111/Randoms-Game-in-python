# Randoms-Game-in-python



































Ramdom Loop in python 

import random
n =20
guessed = int(n * random.random())
guess = 0
while guess != guessed:
    guess = int(input("Please Select your New guessed  number Between 1 - 20 : "))
    if guess > 0:
        if guess > guessed:
            print("Number is too large")
        elif guess < guessed:
            print("Number is too small ")
    else :
        print("Sorry , You are giving up")
        break
else :
    print("Congratulations , You made it dude .")
    
    
                  # By Akshay Bhardwaj
