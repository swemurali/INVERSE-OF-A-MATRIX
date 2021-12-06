# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import the numpy module to use the built-in functions for calculation 
### Step 2: 
prepare the list from each inverse of the matrix and assing in np.array()
### Step 3: 
using the np.linalg.solve(),we can find the solutions.
### Step 4: 
end the program

## Program:
```
#Program to find the inverse of a matrix.
#Developed by:suwetha.M
#RegisterNumber:21006216
import numpy as np
A=np.array([[6,2,3],[3,1,1],[10,3,4]])
ans=np.linalg.inv(A)
print(ans)
```
## Output:
![output](.//image_5.png.png)
## Result:
Thus the inverse of given matrix is successfully solved using python program

