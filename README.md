tabu-search
===========

Tabu Search-Basic algorithms

Elements of a tabu search

The tabu search algorithm combines a few simple ideas into a remarkably efficient framework for heuristic optimization. Among the main elements of this framework are:

1. A (usually) greedy local search; the next solution is usually the best not-yet visited solution in the current neighborhood.
2. A mechanism (the tabu list) discouraging returns to recently visited solutions.
3. A mechanism that changes the solution path (perhaps by a random move) when no progress has been made for a long time.
In addition, many tabu search algorithms incorporate other features such as flexible memory structures and dynamic aspiration criteria (Glover (1995)). 


Although a tabu search is conceptually simple, any implementation of an efficient tabu search algorithm is problem specific, and no generic tabu search software is available at this time. Among the issues faced by designers of tabu search algorithms are:
1.The nature of the information included in the tabu list.
2.The way the tabu list is organized.
3.The lengths of the tabu lists.
4.The types of moves used to create new solutions.
5.The implementation of the local greedy search algorithm.
6.Strategies for diversifying the search when no progress has been made for a while.
