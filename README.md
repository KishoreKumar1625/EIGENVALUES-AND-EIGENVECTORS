# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the NumPy module to use the built in functions for calculations
### Step 2: 
Prepare the given matrix and assign it to np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print the EigenValues and EigenVectors and end the program

## Program:

#Program to find the eigen values and eigen vectors.

#Developed by: Kishore Kumar P

#RegisterNumber:26002452

import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

A = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])

values,vectors = np.linalg.eig(A)

print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))

## Output:<img width="1258" height="767" alt="Screenshot 2026-10-13 211053" src="https://github.com/user-attachments/assets/89a063b3-1e38-44ca-83d8-551ae0e566ef" />
<img width="919" height="163" alt="Screenshot 2026-10-13 211137" src="https://github.com/user-attachments/assets/75162393-7732-49d4-bed0-2daf3914feb0" />
<img width="878" height="139" alt="Screenshot 2026-10-13 211145" src="https://github.com/user-attachments/assets/ca33cfe2-47e2-4aec-928e-86885412f708" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
