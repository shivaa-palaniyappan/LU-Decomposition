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
/*
Program to find the L and U matrix.
Developed by: SHIVAA PALANIYAPPAN V
RegisterNumber: 212223110050
*/
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
/*
Program to find the LU Decomposition of a matrix.
Developed by: SHIVAA PALANIYAPPAN V
RegisterNumber: 212223110050
*/
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
![image](https://github.com/shivaa-palaniyappan/LU-Decomposition/assets/146915611/92377e5c-5919-409e-90fd-def95c19020a)

![image](https://github.com/shivaa-palaniyappan/LU-Decomposition/assets/146915611/ee1173ef-6153-4522-82e5-ebd0d7342a5a)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

