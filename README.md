Technology Used: Python

Introduction:
6x5 Minichess is a compact and fast-paced variant of traditional chess, played on a smaller 6x5 board. It offers strategic depth and quick decision-making, making it an exciting twist on the classic game. With fewer pieces and a condensed battlefield, it's a challenging and engaging chess experience.

Features:
1. MiniChess 6X5 board game(Quick-Chess variant)
2. Choosing between playing against human and computer
3. Game Reset
4. Pawn promotion to latest capture
5. Displaying valid moves upon piece selection
6. If king is in check, the game prevents any other move until the king is protected from the check

Game Mechanics:
1. Base algorithm used for AI: Negamax (variant of Minimax)
2. Alpha-Beta Pruning is used to minimize the game tree
3. Principal Variation Search (PVS) is implemented to enhance Alpha-Beta performance
4. Move ordering is used to increase the efficiency of search and reduce the number of nodes
5. Evaluation is done based on piece score, checkmate, check and piece captured.
6. Valid moves generation of each piece, pin checking are done


