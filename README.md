# Sudoku
Sudoku Solver


#Java #backtracking #sudoku-solver #commandLine 

In this we have used backtracking approch to solve the Sudoku.

So the basic Idea to solve sudoku has 3 check before putting any number in the place in this approch.

1) is number present in row 
2) is number present in column 
3) is numner present in box (3x3) 

If the number to try is not present in above all three check then that number is eligible for that spot, 
so we put that number in the spot and go for another place which is empty ( here empty place denotes by 0).

If we do not find any proper number in another spot then we go to previous spot and check with another eligible number and again go for next spot.

and this will go on untill we find the solution for the sudouku solver, 

if after trying all the possible number, code is not able to find the solution then sudoku is not solvable. 
