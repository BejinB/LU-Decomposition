# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2. from scipy.linalg import lu we can find L and U
3. print L and U
4. end the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: B.Bejin
RegisterNumber: 22001908
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: B.Bejin
RegisterNumber: 22001908
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)

*/
```

## Output:
i,![image](https://user-images.githubusercontent.com/118367518/211834113-8e64c129-33ca-4310-9ef7-652cd2c78015.png)

ii,![image](https://user-images.githubusercontent.com/118367518/211834204-7543bd3b-4d90-4c5e-b8e1-0b67961aef5d.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

