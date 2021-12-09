# Connect-4

# Using Minimax Algorithm to Make Connect 4 AI Agent

 
LAB 2 
Connect-4 game











Sample Run:-
Game interface



- Minimax without alpha-beta pruning



Game tree with depth 3 at first move:-










-Final of Game



- Minimax with alpha-beta pruning:-











-Final of Game:-

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

Depth
MiniMax without pruning
alpha-beta pruning


Time (ms)
Nodes
Time (ms)
Nodes
3
13
400
6
220
5
49
9906
27
3137
7
593
154651
176
25206
9
5035
1831344
852
196718
11
17858
5727785
5653
1586621
13
takes a lot of time
—-------------
38724
8831904



