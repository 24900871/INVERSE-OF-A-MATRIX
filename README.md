# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
   
## Algorithm:
### Step 1: Input Matrix A (square matrix).
### Step 2: Check: Compute the determinant of A.f it is zero, print that the matrix is non-invertible and stop.
### Step 3: Compute: If the determinant is non-zero, use np.linalg.inv(A) to compute the inverse.
### Step 4: Output: Print the inverse matrix.

## Program:
``` python
#Program to find the inverse of a matrix.
#Developed by: JOTHIMANI P
#RegisterNumber: 212224230108
import numpy as np
a=np.array([[2,1,1],[1,1,1],[1,-1,2]])
b=np.linalg.inv(a)
print(b)
```
## Output:

![image](https://github.com/user-attachments/assets/808b4ed0-db57-4980-8463-624af2f36561)

## Result:
Thus the inverse of given matrix is successfully solved using python program
