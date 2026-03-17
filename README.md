# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Algorithm for Finding L and U Matrix

1.Start the program.

2.Import the required libraries numpy and scipy.linalg.

3.Read the matrix A from the user as input.

4.Convert the input matrix into a NumPy array.

5.Apply LU decomposition using the function lu(A) to obtain matrices P, L, and U.

6.Extract the Lower triangular matrix (L) and Upper triangular matrix (U).

7.Display the matrices L and U as the output.

8.Stop the program.

Algorithm for LU Decomposition of a Matrix

1.Start the program.

2.Import the required libraries numpy and scipy.linalg.

3.Read the coefficient matrix A from the user.

4.Read the constant matrix/vector B from the user.

5.Convert both inputs into NumPy arrays.

6.Perform LU factorization using lu_factor(A) to obtain LU matrix and pivot values.

7.Solve the system of equations using lu_solve((lu,pivot), B) to find the solution vector x.

8.Display the solution and stop the program.

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

