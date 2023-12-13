# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## step1:
Import the numpy module to use the built-in functions for calculation
## Step 2:
Prepare the lists from each linear equations and assign in np.array()
## Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the
given matrix.
## Step 4:
End of program


## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: vignesh v
#RegisterNumber:23002301
import numpy as np
a=[[2,-3,0],[2,-5,0],[0,0,3]]
values,vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```

## Output:
<img width="565" alt="image" src="https://github.com/Vickyy-0/EIGENVALUES-AND-EIGENVECTORS/assets/110780412/f5ccd746-3312-4b9b-b4f1-ccc351f3a585">

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
