# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :Import the numpy module to use the built-in functions for calculation
### Step 2:Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:End the Program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Mohamed Mubeen A
#RegisterNumber:212225040241
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np

# Given matrix
a = np.array([[-2, 2, -3],
              [2, 1, -6],
              [-1, -2, 0]])

# Find eigenvalues and eigenvectors
eigen_values, eigen_vectors = np.linalg.eig(a)

print("Eigen values are", eigen_values,end =" ")
print("and Eigen Vectors are",end=" ")
print(eigen_vectors)
```
## Output:
<img width="898" height="219" alt="image" src="https://github.com/user-attachments/assets/11ba8806-7f29-46be-adc5-36655fc0aede" />
 <img width="893" height="206" alt="image" src="https://github.com/user-attachments/assets/973e66e5-072f-4ee1-b142-e34fee716794" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
