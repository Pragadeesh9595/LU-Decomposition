# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Start the program
2.Import the necessary libraries(numpy,scipy.linalg)
3.Define the matrix using numpy
4.Use lu(),lu_solve(),lu_factor() to get the solutions
5.End the program 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: pragadeesh.M
RegisterNumber:25018154 
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
Developed by: pragadeesh.M
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input())) 
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x) 

*/
```

## Output:
![lu decomposition]()
<img width="1002" height="363" alt="Screenshot 2025-12-19 084122" src="https://github.com/user-attachments/assets/4c7ed31f-54b7-4f31-bc81-8d7ae9a2a59a" />
<img width="838" height="176" alt="Screenshot 2025-12-19 084132" src="https://github.com/user-attachments/assets/540fd8b9-dfab-491b-9155-b6c334a6922a" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

