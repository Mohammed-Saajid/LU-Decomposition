# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. Print the variable 'X'

## Program:
(i) To find the L and U matrix
```

Program to find the L and U matrix.

Developed by: MOHAMMED SAAJID S

RegisterNumber: 212223240093

import numpy as np
from scipy.linalg import lu
matrix = np.array(eval(input()))
P,L,U = lu(matrix)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.

Developed by: MOHAMMED SAAJID S

RegisterNumber: 212223240093

import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu,piv),B)
print(X)


*/
```

## Output:

![mathaiexp5i](https://github.com/Mohammed-Saajid/LU-Decomposition/assets/141727149/2f01939d-3d35-4a06-9d40-69d118bb9cee)

![mathaiexp5ii](https://github.com/Mohammed-Saajid/LU-Decomposition/assets/141727149/f6bce22c-b4e9-4bc6-af5d-dbac85647832)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

