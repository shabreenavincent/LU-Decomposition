# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1:
Import numpy library using import statement.

Step 2:
From scipy package import lu().

Step 3:
Get input from user and pass it as an array.

Step 4:
Get P, L, U matrix using lu()

Step 5:
Print L and U matrix

## Program:
(i) To find the L and U matrix


Program to find L and U matrix using LU decomposition.

Developed by: shabreena vincent


RegisterNumber: 212222230141

```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```

## Output:


![lu1](https://user-images.githubusercontent.com/119475721/235623323-31b89b52-823c-4afc-9c33-04621b732adc.png)



(ii) To find the LU Decomposition of a matrix


## AIM:

To write a program to find the LU Decomposition of a matrix.

## Equipments Required:

Hardware – PCs
Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1:
Import numpy library using import statement.

Step 2:
From scipy package import lu_factor() and lu_solve().

Step 3:
Get two inputs from user and pass it as matrix array.

Step 4:
Find lu and pivot value of first matrix using lu_factor().

Step 5:
Find solution of the matrix by using lu_solve() by passing lu, pivot values as first argument and second matrix as second argument.

Step 6:
Print the solution.

## program:

Program to solve a matrix using LU decomposition.

Developed by: shabreena vincent

RegisterNumber: 212222230141



# To print X matrix (solution to the equations)
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
b=eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```


## Output:



![lu2](https://user-images.githubusercontent.com/119475721/235624566-139afc13-14ea-43e4-82e3-5309e3a8c855.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

