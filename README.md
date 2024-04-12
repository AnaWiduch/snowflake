# snowflake
Snowflake Matrix Generator

This Python program generates an n×n matrix with a snowflake pattern. It fills the matrix with '.' symbols and then adds '*' symbols to the middle row, middle column, and diagonals of the matrix.

Input Format:
The input is an odd natural number n (n≥3), representing the number of rows and columns in the matrix.

Output Format:
The program outputs the resulting matrix, where '*' represents the snowflake pattern and '.' represents empty spaces. Elements in the matrix are separated by spaces.

Sample input:
11
Sample output:
* . . . . * . . . . *
. * . . . * . . . * .
. . * . . * . . * . .
. . . * . * . * . . .
. . . . * * * . . . .
* * * * * * * * * * *
. . . . * * * . . . .
. . . * . * . * . . .
. . * . . * . . * . .
. * . . . * . . . * .
* . . . . * . . . . *
