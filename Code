import random

def game():
    listnum=[random.randint(0,9) for n in range(4)]
    print("Solution key: " + str(listnum))
    
    count=0
    while True:
        count+=1
        print("~~~~~Guess: " + str(count)+ "~~~~~")
        
        print("Please guess " + str(4) + "-digit number: ")
        guess = [int(i) for i in str(input())]
        
        if guess == listnum:
            print("You won.")
            print("It took you " + str(count)+ " guess(es).")
            break
            
        else:
            cow = 0
            bull = 0
            
            for x in range(0,4):
                if guess[x]==listnum[x]:
                    cow+=1
                elif guess[x] in listnum:
                    bull+=1
                    
                    
        print("Cows: " + str(cow)+" Bulls: "+str(bull))
        print("++++++++++++")
        
game()
