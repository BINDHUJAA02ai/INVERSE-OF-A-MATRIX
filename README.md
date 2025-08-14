# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: 
### Step 4: 

## Program:
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
    
## Output:
<img width="1143" height="247" alt="Screenshot 2025-08-14 101945" src="https://github.com/user-attachments/assets/c19500b5-86ac-4dcc-83f5-c1ea2da42a95" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

