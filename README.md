# Tic-Tac-Toe

4x4 Tic-Tac-Toe Game in Assembly Language

Project Overview

This project is a 4x4 Tic-Tac-Toe game implemented in assembly language. The game allows two players to play Tic-Tac-Toe on a 4x4 grid, taking turns to place their respective marks (X or O) until one player wins or the game ends in a draw.

Features

4x4 Grid: A larger playing field compared to the traditional 3x3 Tic-Tac-Toe, adding an extra layer of strategy.
Two-Player Mode: Supports two players taking turns on a single machine.
Win Detection: Automatically detects win conditions (horizontal, vertical, and diagonal).
Draw Detection: Detects if the game ends in a draw when all cells are filled without a winner.
Requirements

An x86 assembly language environment 
An emulator or virtual machine capable of running x86 assembly programs.
Basic understanding of assembly language syntax and structure.
Files

tictactoe.asm: The main assembly source code file for the 4x4 Tic-Tac-Toe game.
Makefile: A makefile to compile and link the assembly code (if applicable).
Code Structure

Data Section: Defines the game board and other necessary variables.
Code Section: Contains the main game loop, input handling, win/draw detection, and display functions.
Main Functions
Initialize Board: Sets up the initial empty 4x4 game board.
Display Board: Outputs the current state of the board to the console.
Player Move: Handles player input and updates the board accordingly.
Check Win: Checks if the current move results in a win.
Check Draw: Checks if the board is full, resulting in a draw.
Game Loop: The main loop that continues the game until a win or draw condition is met.


