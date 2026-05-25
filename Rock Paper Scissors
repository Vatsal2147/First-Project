import random
itemList = ["Rock", "Paper", "Scissors"]
stop = False
while(stop ==False):
    userInput = input("Type your move out of rock, paper or scissors, press N for a new game, or Q to quit: ")
    compChoice = random.choice(itemList)
    
    if(userInput=="Q"):
        stop = True
        break
    
    elif(userInput=="N"):
        continue
    
    userInput = userInput.lower()
    
    if(userInput!="rock" and userInput!="paper" and userInput!="scissors"):
        print("That is an invalid move! Try again...")
        continue
    
    if(compChoice=="Rock"):
        print("Your move: ", userInput)
        print("System's move: ", compChoice)
        if(userInput=="rock"):
            print("It's a tie! \n")
        elif(userInput == "scissors"):
            print("You lost! Press N to start a new game or Q to quit\n")
        elif(userInput=="paper"):
            print("You won! Press N to start a new game or Q to quit\n")
        else:
            print("That is an invalid move! Try again...")
            
    elif(compChoice=="Paper"):
        print("Your move: ", userInput)
        print("System's move: ", compChoice)
        if(userInput=="paper"):
            print("It's a tie! \n")
        elif(userInput == "rock"):
            print("You lost! Press N to start a new game or Q to quit\n")
        elif(userInput=="scissors"):
            print("You won! Press N to start a new game or Q to quit\n")
        else:
            print("That is an invalid move! Try again...")
            
    elif(compChoice=="Scissors"):
        print("Your move: ", userInput)
        print("System's move: ", compChoice)
        if(userInput=="scissors"):
            print("It's a tie! \n")
        elif(userInput == "paper"):
            print("You lost! Press N to start a new game or Q to quit\n")
        elif(userInput=="rock"):
            print("You won! Press N to start a new game or Q to quit\n")
        else:
            print("That is an invalid move! Try again...")
            
print("Thank you for playing Rock Paper Scissors") 
