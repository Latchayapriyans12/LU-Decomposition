# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation.
2.Prepare the lists from each linear equations and assign in np.array().
3.Using the scipy.linalg and imort lu_fator and lu_solve we get the values.
4.End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: latchaya priyan s
RegisterNumber: 24900388
*/
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
piv,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
```

(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: latchaya priyan s
RegisterNumber: 24900388
*/
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix=np.array(eval(input()))
b=np.array(eval(input()))
x=lu_factor(matrix)
solution=lu_solve(x,b)
print(solution)
```

## Output:

![Screenshot 2024-12-20 003608](https://github.com/user-attachments/assets/80ffc3c4-2a33-4076-bae1-628b29ac4e2d)

![Screenshot 2024-12-20 003621](https://github.com/user-attachments/assets/e6500b03-5620-4898-8624-e12904ad9f3c)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

