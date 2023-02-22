# AIPacman_Project2_MultiAgent_Search

In this project, I design agents for the classic version of Pacman, including ghosts. I also implemented both minimax, expectimax search and also evaluation the function design.

1)Reflex Agent
Use following commands to test:
python pacman.py --frameTime 0 -p ReflexAgent -k 1
python pacman.py --frameTime 0 -p ReflexAgent -k 2

2)Minimax
Use following commands to test:
python pacman.py -p MinimaxAgent -l minimaxClassic -a depth=4
python pacman.py -p MinimaxAgent -l trappedClassic -a depth=3

3)Alpha-Beta Pruning
Use following commands to test:
python pacman.py -p AlphaBetaAgent -a depth=3 -l smallClassic

4)Expectimax
Use following commands to test:
python pacman.py -p ExpectimaxAgent -l minimaxClassic -a depth=3

