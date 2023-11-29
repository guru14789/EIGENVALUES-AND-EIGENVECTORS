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
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Display the caluclate eigen value and eigen vectors
## Step 5:
End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:SREEKUMAR S
#RegisterNumber:23008070
import numpy as np
a=[[2,2],[1,3]]
values,vectors=np.linalg.eig(a)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")

```

## Output:
![EIGEN](https://github.com/guru14789/EIGENVALUES-AND-EIGENVECTORS/assets/151705853/5cc20835-fc23-4742-b405-4ebd14cbbe51)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.

