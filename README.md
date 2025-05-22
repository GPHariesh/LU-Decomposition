# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
```
 Algorithm To find the L and U matrix
1. Import Required Libraries
2. Input the Matrix
3. Perform LU Decomposition
4. Display L Matrix
5. Display U Matrix

 Algorithm To find the LU Decomposition of a matrix
1. Import Required Libraries
2. Input Matrices A and B
3. Perform LU Factorization
4. Solve the System
5.  Display the Result
```
## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by:G P HARIESH 
RegisterNumber: 212224040100 
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by:G P HARIESH 
RegisterNumber: 212224040100
'''
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
piv,lu=lu_factor(A)
result=lu_solve((piv,lu),B)
print(result)

```

## Output:
![alt text](<Screenshot 2025-04-24 135051.png>) ![alt text](<Screenshot 2025-04-24 135023.png>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

