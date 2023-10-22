# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the module numpy and assign numpy as np
### Step 2: 
Create an variable named 'a' and use np.array() for the matrix values by first list as first row and so on 
### Step 3: 
Create an variable named 'inv' and use np.linalg.inv(a) to inverse the matrix
### Step 4: 
print the value

## Program:
```py 
#Program to find the inverse of a matrix.
#Developed by: vikamuhan 
#RegisterNumber:23012418
import numpy as np
a=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
inv=np.linalg.inv(a)
print(inv)
```
## Output:
![output](./exp%203.png)
## Result:
Thus the inverse of given matrix is successfully solved using python program

