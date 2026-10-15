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

import os
os.environ["OPENBLAS_NUM_THREADS"]= "1"

import numpy as np
matrix = np.array([[6, 2, 3], [3, 1, 1], [10, 3, 4]])
inverse = np.linalg.inv(matrix)
print(inverse)

## Output:
<img width="1218" height="781" alt="{4A1375B8-0DB5-4F30-8379-049219C779A3}" src="https://github.com/user-attachments/assets/6cd5a3dd-7081-4e6b-8979-ec91cc99c109" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

