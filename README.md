# sudoku_game
This project solves a game named sudoku it require pre knowledge of the game sudoku.
# About Game Sudoku:
In this game you have to fill the digits from 0-9 and with the constraints that a digit should not repeat in same row, column or the same box (3x3 box).
# Sudoku in c++:
The project is related to the backtracking and recursion in cpp. We read the user input for a 9x9 matrix which is an form of our unsolved sudoku.Then we show our solved Sudoku in form of a 9x9 matrix and if the solution does not exits then it will print no solution exits.
# User-defined Functions:
print() : To print the resulted solution matrix.
isSafe() : To check whether the passed number is safe according to the given constraints.
solveSudoku() : For the main recursion and backtracking for each empty place which is here is represented by 0.
# Requirements:
You should have MinGw installed in your machine.
Any IDE which supports the cpp language.
# Technologies:
You should have Visual Studio or VS Code pre-installed in your machine to write down the code and to debug the code for your project. Or you can use any other IDE which supports cpp such as code blocks, dev c++, etc.
# Build and Run Instructions:
In order to compile this program firstly you should go in the same directory you have this file (opencv_image_rotation.cpp) using the cd command.
Then type these commands step by step:
g++ sudoku.cpp -o out
out

