# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in mathematical functions.

### Step 2: Define the given matrix as a nested list and assign it to an array using np.array().

### Step 3: Use the np.linalg.inv() function to calculate the inverse of the matrix.

### Step 4: Print the calculated inverse matrix and end the program.

## Program:

import numpy as np
matrix = np.array([[6, 2, 3], [3, 1, 1], [10, 3, 4]])
inverse = np.linalg.inv(matrix)
print(inverse)

## Output:

[[-1. -1.  1.]
 [ 2.  6. -3.]
 [ 1. -2.  0.]]
 
## Result:
Thus the inverse of given matrix is successfully solved using python program

