# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 :
Import the numpy module to use the built-in functions for calculation.

Step 2:
Prepare the lists from each equations and assign in np.array()

Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4:
End the program

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: SATHISH S
#RegisterNumber: 212225040390
import numpy as np
A=np.array([[2,2],[1,3]])
value,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(value,vectors))

## Output:
<img width="1911" height="1062" alt="Screenshot 2026-02-05 093806" src="https://github.com/user-attachments/assets/3374cab0-4fea-4882-b43a-ae54fcc5879d" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
