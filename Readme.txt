This repo was completed as part of the Advanced Topics in Artificial Intelligence subject taught at the Queensland University of Technology. 

The good old wumpus world game: in this repo, an intelligence agent is programmed to navigate through a mxn grid consisting of one wumpus, n pit(s) until it finds the pile of gold or run into the wumpus/pit and die. 

The logic_based_move.py contains code that allows the agent to navigate through the maze using a logical approach: remembering rooms that it has passed and simply find a new path whenever there's a sign of danger (odour from wumpus or breeze from pit). 

The probability_based_move.py contains code that allows the agent to navigate through the maze using a probablisitc approach: weighting the chance that the next room has a wumpus/pit based on given evidence and experience. 

IFN680_AIMA folder contains joint probabilities models used in the main program. 

Probabilistic approached led to much higher survival rate compared to logic-based approach.
