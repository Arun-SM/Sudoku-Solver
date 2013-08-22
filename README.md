Sudoku-Solver
=============

C code to solve SUDOKU

I am uploading my code for the first time, so don't exactly understand what to write here !
Well,
this project contains the C code which solves the very old puzzle SUDOKU programmatically. Approximately taking around 25ms to solve each question.

The code is well tested in gcc compiler. (anyone is free to comment on any line of the code, if you feel anything could have been done). Code uses backtracking approach. (important : code outputs all possible outcomes for a particular question).
For testing purpose I am uaing "test.txt" as the input file to get the input to the program. I am using 0 to indicate blank to make my life easy.



C code to generate SUDOKU

The code uses same methods as used above and efficiently generates a new SUDOKU puzzle everytime. The generated file "test.txt" contains the question, you may use this as input of above code to verify or solve on your own. Again don't be scared of time it takes to generate the question, it purely depends on rand() function, how efficiently your computer is able to generate random numbers at that time. I welcome any suggestion on this.
