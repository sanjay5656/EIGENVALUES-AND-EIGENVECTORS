# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step1 :
Import the numpy module to use the built-in functions for calculation.
## Step 2:
Prepare the lists from each equations and assign in np.array()
## Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
## Step 4:
End the program.
## Program:
Developed by : Sanjay S

Register no  : 212221243002
```python
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
b, c=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(b,c))
```
## Output:
![image](https://github.com/sanjay5656/EIGENVALUES-AND-EIGENVECTORS/assets/115128955/69b3f5a2-f1ae-40a8-88f0-2113ef41edfb)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
