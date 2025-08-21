# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
neter the function import numpy
### Step 2: 
enter the values
### Step 3:
 Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
print the prrogram

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Adhithya Perumal D
#RegisterNumber:212222230007
import numpy as np
A = np.array([[-2, 2, -3],[ 2, 1, -6],[-1,-2,  0]])
eigenvalues,eigenvectors = np.linalg.eig(A)
print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)

```

## Output:
<img width="1256" height="815" alt="Screenshot 2025-08-21 093237" src="https://github.com/user-attachments/assets/d0fd9854-5834-450c-8c0e-5abeeb43d3d1" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
