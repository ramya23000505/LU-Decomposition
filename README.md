# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable. 
4. print the variable 'X'

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: 212223230169
RegisterNumber: RAMYA R
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
pivot,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: 212223230169
RegisterNumber: RAMYA R
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
# To find the L and U matrix
![Screenshot 2024-04-16 085025](https://github.com/ramya23000505/LU-Decomposition/assets/149370791/6ee7a83c-8a93-475e-bb58-8913cad2aa99)
![Screenshot 2024-04-16 085033](https://github.com/ramya23000505/LU-Decomposition/assets/149370791/102ec13a-7891-47d4-b902-c5b292dc24de)
# To find the LU Decomposition of a matrix
![Screenshot 2024-04-16 085040](https://github.com/ramya23000505/LU-Decomposition/assets/149370791/6422ce54-84b9-49db-81d1-b8b4fd2670dd)
![Screenshot 2024-04-16 085048](https://github.com/ramya23000505/LU-Decomposition/assets/149370791/f67874e4-6c53-4506-a5af-9a099c2cd6f7)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

