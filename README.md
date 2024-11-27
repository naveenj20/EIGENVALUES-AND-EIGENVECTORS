# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :  Import the numpy module to use the built-in functions for calculation.
### Step 2: : Prepare the lists from each linear equations and assign in np.array().
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program.

## Program:
```
import numpy as np
a=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {} ".format(values,vectors))
```
## Output:
![Screenshot 2024-11-27 192254](https://github.com/user-attachments/assets/34714a10-42ce-4965-b4ca-5c7bc2b1538a)
![Screenshot 2024-11-27 192304](https://github.com/user-attachments/assets/9a7a28b8-5fc2-4aaa-969b-0dec3f539e43)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
