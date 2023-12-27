# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
```
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner
```
## Algorithm
```
Step1 :
Import the numpy module to use the built-in functions for calculation.
Step 2:
Type the program to be executed.
Step 3:
Using the lu(), we can find the solutions.
Step 4:
Print the value and end the program..
```
## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: Piritharaman R
RegisterNumber: 23013537
```
import numpy as np
from scipy.linalg import lu

A=np.array(eval(input()))
P,L,U= lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: Piritharaman R
RegisterNumber: 23013537
```
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)

```

## Output:
(i) To find the L and U matrix

![image](https://github.com/ramanpiritha/LU-Decomposition/assets/147084116/bb746702-6e1a-4dfe-b18d-3fe8517c8501)

(ii) To find the LU Decomposition of a matrix

![image](https://github.com/ramanpiritha/LU-Decomposition/assets/147084116/e8cbe807-ffc7-4fd7-926f-fed66255ec15)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

