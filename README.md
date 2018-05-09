# Assignment 3

**Due 3/18/2018 at 11:59pm**

### Description

In this assignment you will implment an agent to play t[he game of Connect 4.
Your agent will use the alpha-beta pruning algorithm to select the next move
given the current board state. 

There are two main files:
- ConnectFour.py 
- Player.py

ConnectFour.py contains the all of the functions of the game.
Player.py contains all of the types of players that can participate in the 
game:
- AIPlayer (Your Implementation)
- RandomPlayer (Makes Random Moves)
- HumanPlayer (You)

You need to implement the `get_move()` function in the AIPlayer class. 
You are welcome to implement anyother functions that you think are useful. 
You can't however make any changes to ConnectFour.py

To play the game run the following command:

`python ConnectFour.py arg1 arg2`

Where `arg1` and `arg2` are one of `ai`, `random`, or `human`

For example if you wanted to play against a random player you would run:

`python ConnectFour.py human random`

**Note: A human player has to enter their move into the terminal**

If you wanted your ai to play itself you would run:

`python ConnectFour.py arg1 arg2`

`ConnectFour.py` takes one optional argument `--time` that is an integer. It is
the value used to limit the amount of time in minutes to wait for the AI player
to make a move. The default value is 5 minutes. 

### Deliverables

You will to turn in 2 files:

- Player.py
  - This should include your alpha-beta implementation in the AIPlayer class

- Assignment3.pdf
  - Address the following questions:
    - What heuristic did you use? Why?
    - Describe how your algorithm performs given different time contraints. How much of the tree can you explore given 5 seconds per turn? 10 seconds? 3 seconds? 
    - Can you beat your algorithm?
    - If your algorithm plays itself, does the player that goes first do better or worse in general?

    


