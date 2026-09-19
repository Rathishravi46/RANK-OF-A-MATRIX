# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Input the matrix from the user and store it in a NumPy array.
### Step 2: 
Convert the matrix to row-echelon form using elementary row operations.
### Step 3:
Count the number of non-zero rows in the row-echelon form.
### Step 4:
The number of non-zero rows is the rank of the matrix.

## Program:
```
#Program to find the rank of a matrix.
#Developed by:Rathish R 
#RegisterNumber:212224240132
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrixA=np.array([[1,2,3],[3,6,9]])
result=np.linalg.matrix_rank(matrixA)
print(result)
```
## Output:
<img width="947" height="295" alt="image" src="https://github.com/user-attachments/assets/3f376445-566a-43b0-af53-310ca92c24bc" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

