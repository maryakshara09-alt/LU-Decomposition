# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:MARY AKSHARA S 
RegisterNumber: 2122252320169
*/
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: MARY AKSHARA S
RegisterNumber: 212225230169
*/
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```

## Output:
![lu decomposition]()
<img width="1918" height="977" alt="Screenshot 2026-02-28 202056" src="https://github.com/user-attachments/assets/d7ef8dd3-ddf9-4c36-af68-0976daa66d50" />

<img width="1919" height="1079" alt="Screenshot 2026-02-28 202115" src="https://github.com/user-attachments/assets/1dada236-6870-4014-9b8e-7cc530838e2f" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

