# practical8

Aim: Study of for loop in python

## Theory:
A for loop in Python is used to iterate over a sequence (such as a list, tuple, string, dictionary, set, or range) and execute a block of code repeatedly — once for each item in that sequence.  
The range() function generates a sequence of numbers.  
Break: Stops the loop completely.    
Continue: Skips the current iteration.  
Multiplying two 3x3 Matrix:
for i in range(3):          # rows of a  
  for j in range(3):        # rows of b    
    for k in range(3):    
      result[i][j] += a[i][k] * b[k][j]  
for row in result:  
  print(row)  

## Algoritm:
A)Print Even Numbers from 1 to 10:
Start
Initialize a loop starting at i = 2, ending before 11, with a step increment of 2.
In each iteration, print the current value of i.
End

B)Sum of First n Numbers:
Start
Input an integer value for n.
Initialize a variable sum to 0.
Initialize a loop that iterates from i = 1 to n.
In each iteration, add the value of i to sum.
After the loop finishes, print the final value of sum.
End

C)Print a 3x3 Matrix:
Start
Define a 2D list (matrix) a with 3 rows and 3 columns.
Outer loop: Iterate through each row index i (from 0 to 2).
Inner loop: Iterate through each column index j (from 0 to 2).
Print the element at a[i][j] followed by a space, without moving to a new line.
After the inner loop finishes, print a newline character to move to the next row.
End

D)Matrix Multiplication (3x3):
Start
Define two 3x3 matrices, a and b.
Initialize a 3x3 matrix result filled with 0s.
Outer loop: Iterate through each row i of matrix a.
Middle loop: Iterate through each column j of matrix b.
Inner loop: Iterate through index k (from 0 to 2) to perform dot product.
Calculate result[i][j] = result[i][j] + (a[i][k] * b[k][j]).
After all loops, iterate through each row in result and print it.
End

E)Combinations of 3 Unequal Numbers:
Start
Define a list d containing three distinct numbers (1, 2, 3).
Create three nested loops (i, j, k), each iterating from index 0 to 2.
Check the condition: if d[i] != d[j] AND d[j] != d[k] AND d[i] != d[k].
If the condition is true, print the combination d[i], d[j], d[k].
End

F)Pattern Printing (Right-Angle and Pyramid)
Algorithm for Right-Angle Triangle:
Start
Loop from i = 1 to 9.
In each iteration, print the string "* " multiplied by i.
End
Algorithm for Pyramid Triangle:
Start
Set rows = 5.
Loop from i = 1 to rows.
In each iteration, print spaces equal to (rows - i) followed by the string "* " multiplied by i.
End

G)Print All Prime Numbers (2 to 49):
Start
Outer loop: Iterate n from 2 to 49.
Inner loop: Iterate i from 2 up to n-1.
Check if n is divisible by i (n % i == 0).
If divisible, break the inner loop (not a prime).
If the inner loop completes without a break, print n (it is prime).
End

## Conclusion:
Hence for loop was used in python and programs were done using it.
