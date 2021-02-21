# 1 // Search and Problem Solving
# 2 // Solving problems with AI
Turing Machine: device that can compute anything that is computable.

The term Artificial Intelligence was coined by John McCarthy (1927-2011) – who is often also referred to as the Father of AI.

McCarthy's conjecture at 1956 Dartmouth Conference: that any aspect of learning or intelligence can be so precisely described that a machine can simulate it.

# 3 // Search and Games
Minimax algorithm
: can be used to implement optimal game play in any deterministic, two-player, perfect-information zero-sum game

But in many games, the game tree is simply way too big to traverse in full.

Tricks to manage massive game trees:
1. Heuristic evaluation function:
  * input: board position incl. whose turn is next
  * output: score estimating likely outcome of game continuing
  * example heuristics used (chess): sum of material; positions near board center
  * depth-limited version required to make the problem computationally feasible

The number of states in even a moderately complex real-world scenario grows out of hand, so we can't find a solution by exhaustive search ("brute force"), or even by relying on clever heuristics.

Also, in real life, transitions are not deterministic.
