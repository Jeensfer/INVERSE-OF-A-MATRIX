# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the required libraries os and numpy.
### Step 2: Set the OpenBLAS thread count to 1 using os.environ["OPENBLAS_NUM_THREADS"]="1".
### Step 3: Create the matrix using np.array() and find its inverse using np.linalg.inv().
### Step 4: Display the inverse of the matrix.

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: Jeensfer Jo
#RegisterNumber: 212225240058
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
b=np.linalg.inv(a)
print(b)
```
## Output:
<img width="774" height="820" alt="image" src="https://github.com/user-attachments/assets/54d247d6-4db2-476d-b3f9-9011c406810e" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

