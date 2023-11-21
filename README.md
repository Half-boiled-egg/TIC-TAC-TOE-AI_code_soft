# tic-tac-toe-minimax
An implementation of Minimax AI Algorithm on Tic-Tac-Toe (or Noughts and Crosses) game. Try it: [Tic-tac-toe - Minimax](https://cledersonbc.github.io/tic-tac-toe-minimax/)

## Introduction
To solve games using AI, we will introduce the concept of a game tree followed by minimax algorithm. The different states of the game are represented by nodes in the game tree, very similar to the above planning problems.

## What is Minimax?
Minimax is a artificial intelligence applied in two player games, such as tic-tac-toe, checkers, chess and go. This games are known as zero-sum games, because in a mathematical representation: one player wins (+1) and other player loses (-1) or both of anyone not to win (0).

## How does it works?
The algorithm search, recursively, the best move that leads the *Max* player to win or not lose (draw). It consider the current state of the game and the available moves at that state, then for each valid move it plays (alternating *min* and *max*) until it finds a terminal state (win, draw or lose).
