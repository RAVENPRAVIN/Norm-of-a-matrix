# Norm of a matrix
## Aim
Write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the results in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
#python program to find the 1-Norm of a matrix
#Developed by:PRAVIN KUMAR A.
#Register number:212223230155
# 1-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print('{:.2f}'.format(norm))


# 2-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print('{:.2f}'.format(norm))

# Infinity Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print('{:.2f}'.format(norm))
```
## Output:
### 1-Norm of a Matrix
![N1](https://github.com/RAVENPRAVIN/Norm-of-a-matrix/assets/146820534/c6536903-8f7b-489a-b467-18bc9f7917d3)


### 2-Norm of a Matrix
![N2](https://github.com/RAVENPRAVIN/Norm-of-a-matrix/assets/146820534/26915bd1-e58a-40b2-b991-4f9b89393d08)


### Infinity Norm of the Matrix
![N3](https://github.com/RAVENPRAVIN/Norm-of-a-matrix/assets/146820534/879c5576-0ba0-4930-a36e-63ef13c09141)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix is written and verified.
