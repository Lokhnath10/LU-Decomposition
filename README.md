# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy library using import statement.

2. From scipy package import lu().

3. Get input from user and pass it as an array.

4. Get P, L, U matrix using lu()

5. Print L and U matrix
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Lokhnath J
RegisterNumber: 23004865
*/
```


import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)

(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Lokhnath J
RegisterNumber: 23004865
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![image](https://github.com/Lokhnath10/LU-Decomposition/assets/138969918/ea9fb6cb-7c44-4a72-a481-4c4bb023a0c2)

![Screenshot 2023-11-21 071901](https://github.com/Lokhnath10/LU-Decomposition/assets/138969918/fa5ef094-8dd1-4a0c-be9d-a37c9593fea0)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

