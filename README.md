# Multi-Agent Pacman Search


## Description

Implementation of multi-agent search algorithms in the classic Pac-Man game using Minimax, Alpha-Beta Pruning, and Expectimax techniques.
The project explores adversarial decision-making, stochastic behavior, and heuristic evaluation to optimize Pac-Man’s strategy against ghost agents.
Developed as part of an Artificial Intelligence coursework at Zewail City of Science, Technology and Innovation.

## Objectives

Implement and analyze multi-agent search algorithms.

Develop heuristic functions to evaluate game states.

Optimize decision-making under uncertainty.

Compare algorithm performance and computational efficiency.

### Implemented Agents

| Agent                        | Description                                     |
| ---------------------------- | ----------------------------------------------- |
| **ReflexAgent**              | A reactive agent that uses heuristic evaluation.|
| **MinimaxAgent**             | Adversarial search assuming optimal ghost play. |
| **AlphaBetaAgent**           | Optimized Minimax with pruning for efficiency.  |
| **ExpectimaxAgent**          | Models stochastic (random) ghost behavior.      |
| **BetterEvaluationFunction** | Enhanced heuristic for improved scoring.        |

### How to Run
```
# Play manually
python pacman.py

# Run a specific agent
python pacman.py -p MinimaxAgent -a depth=3

# Evaluate implementation
python autograder.py -q q5 --no-graphics
```
## Key Topics

- Multi-Agent Game Search

- Adversarial and Stochastic Decision-Making

- Heuristic Evaluation and Optimization

- Game Tree Search and Pruning

## Author

**Mai Osama Mohamed Mamoon**

Zewail City of Science, Technology and Innovation


