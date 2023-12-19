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
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
End the program
## Program:
```
#Program to find the rank of a matrix.
#Developed by: S DEEPIKA
#RegisterNumber:23002257
import numpy as np
matrix = np.array([[5,-3,-10] , [2, 2, -3], [-3, -1, 5]])
rank = np.linalg.matrix_rank(matrix)
print(rank)
```
## Output:
![Screenshot 2023-12-19 191059](https://github.com/Deepikasuresh05/RANK-OF-A-MATRIX/assets/148514509/fcdf1279-bfa5-46a6-adf1-e006e31ed1c2)


## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

