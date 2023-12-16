# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Inport numpy module to use built in function for calculation
### Step 2: 
Preapre the list from each linear equation and assign in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
end program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Ajina joshpin
#RegisterNumber:23013547
import numpy as np
a=([[2,2],[1,3]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {}'.format(values,vectors))
```
## Output:
![image](https://github.com/ArchanaSharikalHarinarayanan/EIGENVALUES-AND-EIGENVECTORS/assets/148514578/2e9ee549-1199-47e6-b839-64793e44603f)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
