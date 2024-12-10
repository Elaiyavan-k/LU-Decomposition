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
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: Elaiyavan 
RegisterNumber: 24900184
'''
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
'''Program to solve a matrix using LU decomposition.
Developed by: Elaiyavan K
RegisterNumber: 24900184
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)
```

## Output:

![Screenshot 2024-12-10 081723](https://github.com/user-attachments/assets/97253573-63be-4a95-b0bc-d2e040deca1a)
![Screenshot 2024-12-10 081747](https://github.com/user-attachments/assets/0b554bcc-84ff-4f73-b9c2-6e01ea06a5c7)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

