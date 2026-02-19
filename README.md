# AIM:  Study of For Loop in Python
## THEORY:
A **for** loop in Python is used to iterate over a sequence (such as a list, string, tuple, or a range of numbers). 
Unlike a while loop that keeps running based on a True/False condition, a for loop runs a specific number of times—exactly once for every item in the sequence.
## ALGORITHM:
### 1. Print Numbers from 1 to 5
### Algorithm:

+ Start

+ Initialize a for loop with a variable i in range 1 to 6

+ Print the current value of i.

+ Stop

### 2. Print Odd Numbers from 1 to 10
### Algorithm:

+ Start

+ Initialize a for loop with a variable i starting at 1, ending at 10, with a step increment of 2.

+ Print the current value of i.

+ Repeat step 3 until the loop completes its range.

+ Stop

### 3. Sum of First N Numbers
### Algorithm:

+ Start

+ Get a number from user and store it as an integer in variable n.

+ Initialize a variable total to 0.

+ Start a for loop with variable i ranging from 1 to n+1.

+ In each iteration, add the value of i to total (total = total + i).

+ Once the loop ends, print the final value of total.

+ Stop

### 4. Display a 3x3 Matrix
### Algorithm:

+ Start

+ Define a 3x3 matrix (a list of lists) named A.

+ Start an outer loop with variable i iterating from 0 to 2 (representing the rows).

+ Start an inner loop with variable j iterating from 0 to 2 (representing the columns).

+ Print the element at A[i][j], keeping the output on the same line (separated by a space).

+ When the inner loop finishes, print a new line to move to the next row.

+ Repeat until the outer loop finishes.

+ Stop

### 5. Multiplication of Two 3x3 Matrices
### Algorithm:

+ Start

+ Define two 3x3 matrices, A and B.

+ Initialize a 3x3 matrix named result with all elements set to 0.

+ Start an outer loop i from 0 to 2 (to iterate through rows of A).

+ Start a middle loop j from 0 to 2 (to iterate through columns of B).

+ Start an inner loop k from 0 to 2 (to iterate through rows of B / columns of A).

+ Multiply A[i][k] by B[k][j] and add the product to result[i][j].

+ Once all loops complete, iterate through result row by row and print the final matrix.

+ Stop

### 6. Print All Prime Numbers in a Range (2 to 49)
### Algorithm:

+ Start

+ Start an outer loop with variable i iterating from 2 to 49.

+ Start an inner loop with variable n iterating from 2 to i - 1.

+ Check if i is perfectly divisible by n (i % n == 0).

+ If it is divisible, i is not a prime number; break out of the inner loop immediately.

+ If the inner loop completes without breaking, print i (this means it is a prime number).

+ Repeat for all numbers in the outer loop range.

+ Stop

### 7. Inverted Right-Angle Triangle Pattern
### Algorithm:

+ Start

+ Start a loop with variable i that iterates backward from 5 down to 1.

+ Print an asterisk (*) multiplied by i. (This prints i asterisks on a single line).

+ Repeat until the loop finishes.

+ Stop

### 8. Pyramid Pattern of Stars
### Algorithm:

+ Start

+ Initialize a variable rows with the value 5.

+ Start a loop with variable i iterating from 1 to rows.

+ Calculate the number of leading blank spaces required by subtracting i from rows.

+ Print the calculated spaces followed by the string *  repeated i times.

+ Repeat until the pyramid is fully built.

+ Stop

## CONCLUSION:
We studied about how to use for loop in python and what are the tasks we can perform using for loop.
