# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1: Import the numpy module to use the built-in functions for calculation

Step 2: Prepare the lists from each linear equations and assign in np.array()

Step 3: Using the np.linalg.solve(), we can find the solutions.

Step 4: End the program


## Program:
(i) To find the L and U matrix

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
<img width="1918" height="977" alt="Screenshot 2026-02-28 202056" src="https://github.com/user-attachments/assets/e57f3abf-a8ae-41aa-a464-bb65d3814505" />
<img width="1919" height="1079" alt="Screenshot 2026-02-28 202115" src="https://github.com/user-attachments/assets/e0ca4a3c-5124-4be0-87cc-13baaf31a449" />





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

