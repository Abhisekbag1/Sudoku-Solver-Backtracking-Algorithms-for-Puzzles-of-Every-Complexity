# Sudoku-Solver-Backtracking-Algorithms-for-Puzzles-of-Every-Complexity
# Abstract:
Sudoku game is well famous and popular game among many players all over the world. This
report details the development of a Sudoku game application that is written in Java. The
application is even developed to work in Android systems.
In addition, the report details the implementation of the complexity of the algorithms used to
solve any kind of Sudoku puzzle. Also, how to generate a puzzle with different level of
difficulties and make sure there will be only one solution.
The aim of the report is also to discuss the backtracking, brute force algorithms and other logics
in order to create and solve Sudoku puzzles. Furthermore, the user-friendly environment is
considered in the report as the rules of Sudoku are connected to the interface.
Moreover, the report specifics how well these methods of solving solves the puzzle and
achieved the goal of this implementation. The report concludes by evaluating the end
application to analyse how good it met its objectives and the performance of solving
algorithms. Finally, the report summarises the overall achievements of the application
development and indicates other possible extensions.

# INTRODUCTION:
Originally, Sudoku is a Japanese puzzle game. It means "Single Number" or "Number Place".
The game consists of a 9x9 grid, which is divided into nine 3x3 grids (called boxes or subgrids). So, there are 9 rows and 9 columns. The intersection of a row and a column is called a
cell. The result of the total cells is 81. The objective is to fill the empty cells with only one
number from 1 to 9 in the shortest time. There are 3 rules in order to complete and accomplish
all of the empty cells:
1) The number must only occur in a column once.
2) The number must only occur in a row once.
3) The number must occur in a sub-grid only once.
Moreover, Sudoku is a popular and intellectually stimulating puzzle game that challenges one's
logical thinking and problem-solving abilities. Many individuals, from novices to experienced
players, often seek efficient solutions to Sudoku puzzles. This project serves to fulfill that need
by providing an algorithmic tool for solving Sudoku puzzles. This means that the solution of
any puzzle should have one solution that is unique. The difficulty of the puzzle depends not
only how many numbers are given, but also on the placement of the given cells.

# Identification of Tasks:
identified and executed. These tasks can be categorized into different phases, starting
from project planning and ending with deployment and potential future improvements.
Here are the key tasks involved:
1. Project Planning and Research:
Define project objectives and scope.
Research Sudoku rules and strategies.
Choose the programming language and development environment.
Identify and evaluate relevant libraries or frameworks.
2. Puzzle Generation:
Develop a puzzle generation algorithm to create Sudoku puzzles of varying difficulty
levels.
Ensure the puzzles have unique solutions.
3. Backtracking Algorithm:
Implement the backtracking algorithm for solving Sudoku puzzles.
Handle constraints and backtrack when necessary.
Optimize the algorithm for efficiency.
4. Constraint Satisfaction:
Explore and implement constraint satisfaction libraries or techniques to enhance the
solving process.
5. User Interface:
Design and develop a user-friendly interface for inputting and displaying Sudoku
puzzles.
Create a mechanism for selecting puzzle difficulty levels.

# Pencil-And-Paper Algorithm: 
```bash
Pencil-and-paper (puzzle [][]){
puzzle [][]
Solve the puzzle{
For 1 to 10
Naked Single Method (puzzle[][])
check all rows (puzzle[][]) //check if there is only one candidate
that
is missing, place that missing digit in the empty square
check all columns (puzzle[][])
check all boxes (puzzle[][])
}
If the puzzle is solved: print
Otherwise: recursiveBacktracking (puzzle[][])
Print the solved puzzle
}
```

# The Backtracking algorithm: 
```bash
recursiveBacktrackning(Puzzle[][]){
Puzzle [][] //global
solvePuzzle(row,col){
if (no more choices): the puzzle is solved!
If (puzzle[row][col]= notEmpty):
move to the next square.
for 1 to 9: if(checkRow(row,col,digit) & checkCol(row,col,digit) &
checkBox(row,col,digit){
puzzle[row][col]= digit;
move to the next square
}
if not valid number is found go the previous square that was recently filled
}
}
```
# Conclusion:
The Sudoku Solver project, with its focus on providing a comprehensive solution for
Sudoku puzzle enthusiasts, is expected to yield positive outcomes. The anticipated
results include the successful development of a user-friendly application capable of
solving Sudoku puzzles of varying difficulty levels. This application will offer a rich
user experience, incorporating features such as puzzle generation, customization, hint
systems, and accessibility enhancements. It will provide efficient and accurate
solutions to Sudoku puzzles while safeguarding user data and privacy.

# AUTHORS:
1. ABHISEK BAG/21BCS9333@cuchd.in
2. Khushi Ranjana/21BCS9320@cuchd.in
3. Pragya/21BCS9346@cuchd.in
