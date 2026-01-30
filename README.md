# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import NumPy and create matrix A.
### Step 2: Find eigenvalues and eigenvectors of A.
### Step 3: Store them in variables.
### Step 4: Print the result.

## Program:
```
import numpy as np

A=np.array([[4,2],[2,4]])

values,vectors=np.linalg.eig(A)

print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```
## Output:
<img width="687" height="918" alt="image" src="https://github.com/user-attachments/assets/18cc3919-8af8-42fa-a922-4036564acb5b" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
