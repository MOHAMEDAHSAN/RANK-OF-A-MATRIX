# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import numpy module as np
### Step 2: 
Using np.array() create a matrix for which the rank is to be found
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:
Display the rank of the matrix using print() 
## Program:
~~~Python
#Program to find the rank of a matrix.
#Developed by: S MOHAMED AHSAN
#RegisterNumber: 23001044
import numpy as np
a=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
print(np.linalg.matrix_rank(a))
~~~
## Output:
![rank](/Rank.png)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

