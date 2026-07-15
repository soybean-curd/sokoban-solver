# Sokoban AI Solver
An AI bot that solves Sokoban puzzles using IDA* search.

Built on top of a provided game engine (GUI, map loader, game loop)
for a university course. The solver package was designed and 
implemented independently.

## My Contribution
- solver/SokoBot.java   — IDA* search algorithm
- solver/State.java     — State representation and path reconstruction
- solver/Heuristic.java — Greedy unique goal assignment heuristic
- solver/Deadlock.java  — Corner, edge, and square deadlock detection
