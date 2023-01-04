# Create-a-number-guessing-game
#Number guessing game
n=56
print("Guess a number")
while 5:
    num=int(input("Enter your number\n"))
    if num==56:
        print("You guess a right")
        break
    elif num<56:
        print("Your enter number is lowest enter number between 54 to 56")
        continue
    elif num>56:
        print("You enter the biggest number enter number between 55 to 56")
        continue
    else:
        print("GAME OVER")
        break
