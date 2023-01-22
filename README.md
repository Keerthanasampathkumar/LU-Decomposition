# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

Step 1: Import numpy library using import statement.

Step 2: From scipy package import lu().

Step 3: Get input from user and pass it as an array.

Step 4: Get P, L, U matrix using lu()

Step 5: Print L and U matrix

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: KEERTHANA S
RegisterNumber: 22009006
import numpy as np
import scipy
from scipy.linalg import lu
a=eval(input())
p,l,u=lu(a)
print(l)
print(u)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: KEERTHANA S
RegisterNumber: 22009006
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A =eval(input())
B =eval(input())
lu,piv= lu_factor(A)
x= lu_solve((lu,piv),B)
print(x)
*/
```

## Output:
![Screenshot 2023-01-22 180619](https://user-images.githubusercontent.com/119477890/213916188-78f73b1b-0638-452b-8c3a-c5990c3cbea7.png)

![Screenshot 2023-01-22 180716](https://user-images.githubusercontent.com/119477890/213916228-761fbae3-cb8a-43aa-9071-05c4188fdb49.png)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

