# Rock, Paper, Scissors!

## (Stein, Papier, Schere)

Our goal today is to plan and design a program that allows a player to play `rock, paper, scissors' with the computer. 

At every round, the player must choose either 'rock', 'paper' or 'scissors'. 
The computer then makes a random choice and decides its move. 

We can then compare the player input and the computer decision to decide who won! 

Consider of course that invalid answers are not accepted. 
An invalid answer is anything other than rock, paper or scissors. 

## Plan the program

The internal algorithm that our program must follow is:
    
1. Define a list with strings for the possible choices the players can make
2. Define a variable that takes the player input (`player = input()` can be useful here. The `input()` function waits until the player has typed something in the terminal)
3. We check the value the player entered against the list of choices and we determine if the input is valid. E.g. the option `steineeee` is not valid.
4. Define the computer's "choice" by selecting a random choice from the available possibilities (The `random` module is helpful in this case)
5. Compare the player variable vs. the computer variable and determine the winner.
6. Repeat until the player quits the game. 

## Write the program

TASK: carry out the above algorithm in Python! 

Don't be afraid to look for answers or examples in Google. 
Programming is 50% planning and 50% looking how to do stuff online! 

## Online resources and help

Don't forget to import the "random" library to your script! (`import random`)
Try [this link](https://www.w3schools.com/python/ref_random_choice.asp) to see how the `random.choice()` method works. 


