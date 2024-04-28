# EX07 Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:

# i)Program to find 1-norm of a matrix:
```
#Program to find 1-norm of a matrix
#Developed by: HARINI R
#Register number: 212223100010

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
# ii)Program to find 2-norm of a matrix
```
#Program to find 2-norm of a matrix.
#Developed by: HARINI R
#RegisterNumber: 212223100010

import numpy as np
# Type your code here
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```

# iii)Program to find infinity-norm of a matrix.
```
#Program to find infinity-norm of a matrix.
#Developed by: HARINI R
#RegisterNumber: 212223100010

import numpy as np
# Type your code here
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![alt text](1.png)

### 2-Norm of a Matrix
![alt text](2.png)

### Infinity Norm of a Matrix
![alt text](inf.png)

## Result:
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
