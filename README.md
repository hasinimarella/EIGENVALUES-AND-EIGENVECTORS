# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Enter the code
### Step 2: 
Get the correct values from the user
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the code
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: MARELLA HASINI
#RegisterNumber:23012757
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![OUTPUT](<Eigen valuesand Eigen vectors-1.png>)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
