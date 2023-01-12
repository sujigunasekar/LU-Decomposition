# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
step 1:
Import the numpy module to use the built-in functions for calculation

Step 2:
Prepare the lists from each linear equations and assign in np.array()

Step 3:
From scipy.linalg import lu, we can find the solutions .

Step 4:
End the program


## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by:Suji.G 
RegisterNumber: 22008563
'''
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Suji.G
RegisterNumber: 22008563
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

![![Screenshot from 2023-01-12 09-27-06](https://user-images.githubusercontent.com/119559822/211972911-27a4041d-24bb-4799-8c7a-a692828a6bb7.png)
![Screenshot from 2023-01-12 09-27-37](https://user-images.githubusercontent.com/119559822/211972861-47bc45f1-a664-4545-9e5e-f55dca1c688b.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

