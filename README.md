# Guess-the-number
n=15     #Guess number
guess=0
print("you have only 5 times to guess")
while(True):
    num = int(input ("Enter the number="))
    guess = guess + 1
    if  guess==5:
        print("Game over")
        break
    elif num>n:
        print("do less ")
        print("Guess left ",5-guess)
    elif num<n :
        print("Do more")
        print("Guess left",5-guess)
    elif num==n:
        print("You guess the right number ")
        print(" Attempt no:",guess)
        break
