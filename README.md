# EXP - 04
# DATE : 01/09/24
# EIGEN VALUES AND EIGEN VECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import numpy
### Step 2: create a array give values
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: end the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Saravanan C
#RegisterNumber: 212222110041
import numpy as np
A = np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vector = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vector))
```


## Output:
![EXP - 04 Eigen Values and Eigen Vector](https://github.com/user-attachments/assets/0a954eb3-ed37-4867-97ff-b38e0344bbe8)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
