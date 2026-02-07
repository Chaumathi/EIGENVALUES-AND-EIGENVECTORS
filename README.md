# EIGENVALUES-AND-EIGENVECTORS
NAME : CHARUMATHI A 
REG NO. : 21224230045
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Read the given square matrix.
### Step 2: Import the NumPy library and store the matrix in array form.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Display the eigenvalues and the corresponding eigenvectors.

## Program:
```
import numpy as np

A = np.array([[-2,  2, -3],
              [ 2,  1, -6],
              [-1, -2,  0]])

values, vectors = np.linalg.eig(A)

print("Eigen values are", values, "and Eigen Vectors are", vectors)
```
## Output:
<img width="1380" height="910" alt="image" src="https://github.com/user-attachments/assets/0ae34dce-5c54-48bd-9cab-738f30696db1" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
