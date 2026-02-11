# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :  Import NumPy library, np.linalg is its linear algebra module, which provides the eig() function to compute eigenvalues and eigenvectors.
### Step 2: Create a square matrix, Eigenvalues and eigenvectors can only be found for square matrices (same number of rows and columns).
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the result, This line displays the eigenvalues and eigenvectors.

## Program:

''''''
import numpy as np
matrix = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
eigen_values,eigen_vectors = np.linalg.eig(matrix)
print("Eigen values are {} and Eigen Vectors are {}".format(eigen_values,eigen_vectors))
''''''

## Output:![Exp4_image](<Screenshot 2026-02-11 233417.png>)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
