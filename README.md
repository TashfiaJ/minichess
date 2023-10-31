Technology Used: Python

Introduction:
6x5 Minichess is a compact and fast-paced variant of traditional chess, played on a smaller 6x5 board. It offers strategic depth and quick decision-making, making it an exciting twist on the classic game. With fewer pieces and a condensed battlefield, it's a challenging and engaging chess experience.

Features:
MiniChess 6X5 board game(Quick-Chess variant)
Choosing between playing against human and computer
Game Reset
Pawn promotion to latest capture
Displaying valid moves upon piece selection
If king is in check, the game prevents any other move until the king is protected from the check

Game Mechanics:
Base algorithm used for AI: Negamax (variant of Minimax)
Alpha-Beta Pruning is used to minimize the game tree
Principal Variation Search (PVS) is implemented to enhance Alpha-Beta performance
Move ordering is used to increase the efficiency of search and reduce the number of nodes
Evaluation is done based on piece score, checkmate, check and piece captured.
Valid moves generation of each piece, pin checking are done


