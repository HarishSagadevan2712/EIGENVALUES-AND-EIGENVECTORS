# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use the built-in functions for calculation

### Step 2:
Prepare the lists from each linear equations and assign in np.array()

### Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4:
End the program


## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: HARISH S
#RegisterNumber:212224110022
import numpy as np

# Define the matrix
matrix = np.array([[-2, 2, -3],
                   [2, 1, -6],
                   [-1, -2, 0]])

eigenvalues, eigenvectors = np.linalg.eig(matrix)

print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")
```
## Output:
![Screenshot 2025-05-21 133335](https://github.com/user-attachments/assets/3cd68624-efb5-4e5e-a153-ef4cb15c0297)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
