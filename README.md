# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Start the program and import the NumPy library.
### Step 2: Set the environment variable OPENBLAS_NUM_THREADS to 1 to limit the number of OpenBLAS threads.
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Store the calculated rank in the variable solution and display the result using print(solution). Then Stop.
## Program:
```
#Program to find the rank of a matrix.
#Developed by:chandru v
#RegisterNumber:212224230043
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[3,2,5],[1,1,2],[3,3,6]])
solution=np.linalg.matrix_rank(a)
print(solution)
```
## Output:

<img width="967" height="352" alt="image" src="https://github.com/user-attachments/assets/ab544fb9-37d0-4059-9d70-87f224cfc4b5" />


## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

