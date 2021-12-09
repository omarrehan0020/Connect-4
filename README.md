# Connect-4

# Using Minimax Algorithm to Make Connect 4 AI Agent

 
LAB 2 
Connect-4 game











Sample Run:-
Game interface
![11](https://user-images.githubusercontent.com/59891874/145469107-d41a4c42-50a0-4a47-90d8-d5c1d4d30fc3.PNG)




![222](https://user-images.githubusercontent.com/59891874/145469296-b1e123da-b165-4985-8afa-99f11482544b.PNG)



-end of Game

![333333](https://user-images.githubusercontent.com/59891874/145469426-220d301b-2514-4cec-a07a-540e1a88a0e5.PNG)







heuristic
Calculate score =  total points of computer – total points of players
For every four neighboring  chips in the same row or  In the same column or Diagonally
If the four chips are empty or has computer & player chips   do nothing 
If the four chips are for computer  add 900,000 to the score 
If the four chips are for player  subtract 900,000 to the score 
If  three chips are for computer and one is empty  add 300,000 to the score 
If three chips are for the player and one is empty  subtract 300,000 to the score 
If  two  chips are for computer and two are empty  add 500 to the score 
If two  chips are for the player and two are empty   subtract 500 to the score 
If  one  chip is for the computer and three are empty  add 200 to the score 
If one chip is for the player and three are empty  subtract 200 to the score 


Data structures:
 List: use to store the children of every explored state in the game
 HashMap: used to store the visited states of the games, this hashmap helps to speed the Minimax Algorithm buy avoid researching an already explored state

Time:
All Calculations are done on the First Step:


![44444](https://user-images.githubusercontent.com/59891874/145469568-fb0f5ee7-776a-40f5-b4ed-58a3c611a5d3.PNG)

