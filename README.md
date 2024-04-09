# EIGENVALUES-AND-EIGENVECTORS
# DATE: 06/04/2024
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation.
### Step 2: Prepare the lists from each equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program
## Program:
/*
# program to implement univariant linear regression to fit a straight line using least s.
# Developed by:KISHORE.M
# Register Number: 2305002012
*/
```
import numpy as np
A=np.array([[2,2],[1,3]])
E,EV=np.linalg.eig(A)
print("Eigen values are\n",E,"\nEigen vectors are:\n",EV)
```
## Output:
#4 Program to find the eigen values and eigen vectors of the matrix [2,2], [1,3]
#Developed by: Kishore M
#RegisterNumber: 2305002012
<img width="785" alt="eigen" src="https://github.com/kishore07062005/EIGENVALUES-AND-EIGENVECTORS/assets/156066116/05f28ae0-93a7-415b-a695-5ba0c4d3d675">

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
