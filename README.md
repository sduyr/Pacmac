PacMan Project
======================

Reflex Agent
------------
$python pacman.py -p ReflexAgent -l testClassic

$python pacman.py --frameTime 0 -p ReflexAgent -k 1

$python pacman.py --frameTime 0 -p ReflexAgent -k 2

Minimax
-------
$python pacman.py -p MinimaxAgent -l minimaxClassic -a depth=4

$python pacman.py -p MinimaxAgent -l trappedClassic -a depth=3

Alpha-Beta Pruning
------------------
$python pacman.py -p AlphaBetaAgent -a depth=3 -l smallClassic

Expectimax
----------
$python pacman.py -p ExpectimaxAgent -l minimaxClassic -a depth=3

$python pacman.py -p AlphaBetaAgent -l trappedClassic -a depth=3 -q -n 10

$python pacman.py -p ExpectimaxAgent -l trappedClassic -a depth=3 -q -n 10

Evaluation Function
-------------------
$python autograder.py -q q5

