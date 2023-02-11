# MazeSolver

This project is a solution for maze navigation using a depth-first search algorithm. The maze is represented in the form of a 2D array, where the walls are represented by "#" and the open paths are represented by " ". The algorithm search for the start point and searches for the end point by exploring all possible paths in a depth-first manner until it finds a path that leads to the end. The solution is then outputted as a series of steps indicating the path taken to reach the end.

The result of the maze solver can be seen in the file result.txt, which shows the path from the start to the end of the maze. The path is represented by the "." character. The project also displays the execution time and provides a simple interaction with the user, allowing them to choose the input file.

## Usage

To run the project, simply execute the `main.py` file using a Python interpreter. Follow the on-screen instructions to select the input file and run the algorithm. If you want to use your own maze, don't forget to put the txt file of it in /mazes folder.

## Input format

The input file should contain the maze representation, with walls represented by `#` characters and open paths represented by ` ` (spaces). The start and end points of the maze should be clearly marked in the file with 'S' representing Start and 'E' representing the End.
