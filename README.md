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
4. print the variable 'X'

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: SANJAI L
RegisterNumber: 212223230184

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: SANJAI L
RegisterNumber:212223230184

import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)
```

## Output:
(i) To find the L and U matrix
![image](https://github.com/SanjaiOfficial/LU-Decomposition/assets/151763180/6312c21e-e0d4-424a-878e-9754f3eb684d)
![image](https://github.com/SanjaiOfficial/LU-Decomposition/assets/151763180/b1a9d415-7d71-478a-91dd-12eb131a3b75)
(ii) To find the LU Decomposition of a matrix
![image](https://github.com/SanjaiOfficial/LU-Decomposition/assets/151763180/4c7993e7-e496-4874-8b57-090628a99c21)
![image](https://github.com/SanjaiOfficial/LU-Decomposition/assets/151763180/17ded43a-a6c9-464e-b192-3c3e066205e3)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

