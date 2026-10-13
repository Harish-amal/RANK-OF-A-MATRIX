# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Take the given list and assign in np.array()
### Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
print and end the program
## Program:
import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy

a=numpy.array([[1,2,3],[3,6,9]])

b=numpy.linalg.matrix_rank(a)

print(b)
## Output:
<img width="882" height="842" alt="image" src="https://github.com/user-attachments/assets/8d3c69bb-cfb1-492e-863d-1374d3b2c3e2" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

