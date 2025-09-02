# LU Decomposition 
```
Name : W Allen Johnston Ozario
Reg. No : 212224110004
```
## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1:
Import required libraries numpy and scipy.linalg.

Step 2:
Input the matrix/matrices using eval(input()).

Step 3:
Perform LU decomposition using lu() or solve equations using lu_factor() and lu_solve().

Step 4:
Print the results L and U matrices or solution X matrix.

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: W Allen Johnston Ozario
RegisterNumber: 212224110004

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: W Allen Johnston Ozario
RegisterNumber: 212224110004

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a = np.array(eval(input()))
b = np.array(eval(input()))
l,p = lu_factor(a)
x = lu_solve((l,p),b)

print(x)
```

## Output:
(i) To find the L and U matrix:
<img width="1354" height="982" alt="image" src="https://github.com/user-attachments/assets/b978e448-4041-49ee-b61f-4e3ce204c7c9" />

(ii) To find the LU Decomposition of a matrix:
<img width="1350" height="813" alt="image" src="https://github.com/user-attachments/assets/e3b9a875-81a7-42d2-9d74-8cebf9f0d980" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

