# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import the numpy module to use the built-in functions for calculation.

2.Import the numpy module to use the built-in functions for calculation.

3.Using the np.linalg.norm,we get result.

4.End the program.

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Mugil
RegisterNumber: 212223230127
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
Developed by: Mugil
RegisterNumber: 212223230127
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![lu decomposition]()
(i)
![image](https://github.com/mugil25/LU-Decomposition/assets/148515771/6386a098-70d6-4b35-8703-1ec6f8bd465c)

(ii)

![image](https://github.com/mugil25/LU-Decomposition/assets/148515771/b1480b32-a2c1-4902-a9dc-9124095bf1cc)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

