# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import the lu function scipy.linalg for LU decomposition.
2. convert the input string to a numpy array using the eval() function.
3. use the lu() function to decompose the matrix A into P,and U
4. print the L matrix and U matrix 

## Program:
(i) To find the L and U matrix
```

'''Program to find L and U matrix using LU decomposition.
Developed by: G SAI GURU CHANDRAN
RegisterNumber: 23014037
'''
#TO PRINT L AND U MATRIX
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U) 

```
(ii) To find the LU Decomposition of a matrix
```

'''
Program to solve a matrix using LU decomposition.
Developed by: SAI GURU CHANDRAN G
RegisterNumber: 23014037
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu,piv = lu_factor(A)
x = lu_solve((lu,piv),b)
print (x)


```

## Output:
(i) To find the L and U matrix
![Screenshot 2023-12-30 173658](https://github.com/Saiguruchandran/LU-Decomposition/assets/144870946/d92d6c66-077d-43c7-9ae7-3872869ec030)

(ii) To find the LU Decomposition of a matrix
![Screenshot 2023-12-30 173719](https://github.com/Saiguruchandran/LU-Decomposition/assets/144870946/4a51be72-c095-467f-a745-aa6bb05817b2)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

