# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : A 3x3 matrix is provided as input.  
### Step 2: np.linalg.eig() computes both eigenvalues and the corresponding eigenvectors.
The eigenvalues are the roots of the characteristic equation det(a−λI)=0, where λ is the eigenvalue.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: The eigenvectors are the non-zero vectors that satisfy (a−λI)v=0.
## Program:
```
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![Screenshot 2024-12-04 154426](https://github.com/user-attachments/assets/a5f52787-cd29-46b0-8924-6e0f8897bece)
![Screenshot 2024-12-04 154442](https://github.com/user-attachments/assets/3a8095d1-fcf8-482a-8686-8a51e42245f6)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
