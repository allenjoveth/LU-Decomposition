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
Developed by: Allen Joveth P
RegisterNumber:23009582
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Allen Joveth P
RegisterNumber: 23009582
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)
*/
```

## Output:
LU Decomposition

![Screenshot 2023-12-21 202717](https://github.com/allenjoveth/LU-Decomposition/assets/139422287/2aca930b-88a8-4cae-8354-c45873de31bb)

![Screenshot 2023-12-21 203143](https://github.com/allenjoveth/LU-Decomposition/assets/139422287/374e7cc2-7fb1-4506-bf8f-c91f3f74e1f9)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

