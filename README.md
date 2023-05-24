# `NIM GAME`
Simulates the game of Nim, in which two players alternate in removing the stones arranged in piles. On each turn, a player must remove one or more stones, provided all stones come from the same pile. The player that takes the last stone/s from the only remaining pile wins the game. First, go to the following site to play the game a few times to understand how it is played: (the piles are arranged in columns and clicking on a specific dot indicate

# 'Min-Max Algorithm'
Mini-max algorithm is a recursive or backtracking algorithm which is used in decision-making and game theory. It provides an optimal move for the player assuming that opponent is also playing optimally.
Mini-Max algorithm uses recursion to search through the game-tree.
Min-Max algorithm is mostly used for game playing in AI. Such as Chess, Checkers, tic-tac-toe, go, and various tow-players game. This Algorithm computes the minimax decision for the current state.
In this algorithm two players play the game, one is called MAX and other is called MIN.
Both the players fight it as the opponent player gets the minimum benefit while they get the maximum benefit.
Both Players of the game are opponent of each other, where MAX will select the maximized value and MIN will select the minimized value.
The minimax algorithm performs a depth-first search algorithm for the exploration of the complete game tree.
The minimax algorithm proceeds all the way down to the terminal node of the tree, then backtrack the tree as the recursion.
 
 ![image](https://github.com/Siddhipatade/NIM-GAME/assets/91780318/5e396ab9-44ac-4d23-b6ca-521dcd4fe9ca)


## Nim game should proceed as follows:
1.	Ask player 1 for his name
2.	Ask player 2 for his name
3.	Use random number generator to generate between 2 to 5 piles and to generate between 1 to 8 stones in each pile.
4.	Display the board in the following fashion: (Note: O is the letter capital O)

    Pile 1: O O O 
 
    Pile 2: O
    
    Pile 3: O O
    
    Pile 4: O O O O O O O O
  
5.	Ask player 1 for the move – the pile number and the number of stones to remove. You need to make sure that if a user enters something invalid, whether the pile or stone number, you ask for input again until valid input is entered. Also, the program is to give a suggestion to player 1 as to the number of stones to remove and from which pile in order to win the game. The winning strategy that is to be proposed by the program is explained later on in this document.
6.	Repeat step 4
7.	Repeat step 5 for player 2.
8.	When the game terminates, you need to proclaim the winner.
9.	You should ask, if the players want to play the game again; if so, repeat steps 1-9
You are given a sample program run below – make sure your prompts look like the ones provided in the sample run.
