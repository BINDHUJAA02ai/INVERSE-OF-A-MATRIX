# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import numpy module to use the built in functions for calculation.
### Step 2: Prepare the lists from each linear equations and assign in np.array().
### Step 3: Using the np.linalg.inv(), we can find the inverse of the given matrix.
### Step 4: End the program.

## Program:
```

#Developed by: Bindhujaa S
#RegisterNumber:212224230038

import numpy as np
A = np.array([[1, 0, 3],
              [-1, 2, -2],
              [2, 3, -1]])
det = np.linalg.det(A)
if det == 0:
    print("Matrix is not invertible")
else:
    A_inv = np.linalg.inv(A)
    print(A_inv)
```
    
## Output:
<img width="1265" height="872" alt="image" src="https://github.com/user-attachments/assets/2897b9fe-0408-4d01-8ac4-371a5da16d13" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

