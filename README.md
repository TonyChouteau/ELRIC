# ELRIC

## Introduction

ELRIC is a group project consisting in familiarizing oneself with AI techniques through board games (TicTacToe, Connect4, Chess).

The initial project was to build a chess AI, the first step of the project was to create a chess engine in C. 

Then we started to look for the AI itself. For this we started on a small scale, on simpler games such as TicTacToe or Connect4.

## Version II

On this second version, the Elric AI use the MinMax algorithme :

The AI will explore the tree of possibilities by keeping the best move if it is the AI's turn or by simulating the opposing player taking the worst move when it is not his turn.

Unlike Monte Carlo, MinMax takes into account that the opposing player will play the best move for him, not random moves.

Elric TicTacToe v2 : https://github.com/TonyChouteau/ElricT3_v2

Elric Connect4 v2 : IN PROGRESS ...

## Version I

The first version of the Elric AI use the MonteCarlo algorithme : 

The AI will play, in a hidden way, a lot of random play based on the current state of the board, and will play the move that most often results in victory.

Elric TicTacToe v1 : https://github.com/TonyChouteau/ElricT3_v1

Elric Connect4 v1 : https://github.com/TonyChouteau/ElricConnect4_v1

In a few tries, we noticed that this algorithm was vulnerable to simple strategies. 

So we didn't export it to chess which is an even more complex game.
