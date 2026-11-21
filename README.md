# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import the numpy module to use the built-in function for calculation
### Step 2: prepare the list from each linear equation assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: end the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: R.TEJASWINI
#RegisterNumber: 212224230218
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a= np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
```

## Output:

<img width="1297" height="921" alt="image" src="https://github.com/user-attachments/assets/2497e516-d46b-47df-986b-26c5e7912037" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
