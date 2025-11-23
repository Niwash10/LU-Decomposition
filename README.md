# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy library
2. Check if the matrix is valid for LU decomposition
3. Perform LU decomposition
4. Extract the L and U matrices
5. print the results

## Program:
~~~
(i) To find the L and U matrix
/*
Program to find the L and U matrix.
Developed by: Niwash.K
RegisterNumber: 25014908
*/
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
~~~

<img width="1244" height="669" alt="Screenshot 2025-11-23 101333" src="https://github.com/user-attachments/assets/52c9b6f7-baef-4d49-9dfc-768c2b91cdff" />






(ii) To find the LU Decomposition of a matrix
~~~
/*
Program to find the LU Decomposition of a matrix.
Developed by: Niwash.K
RegisterNumber:25014908 
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,pivot=lu_factor(a)
x=lu_solve((lu,pivot),b)
print(x)
~~~

<img width="1215" height="796" alt="Screenshot 2025-11-23 101455" src="https://github.com/user-attachments/assets/26b539d6-02b2-463b-9863-8c116b8a37b3" />



## Output:
(i) To find the L and U matrix

<img width="1232" height="576" alt="image" src="https://github.com/user-attachments/assets/7b6bdb3b-6ee1-41f0-9894-1f811c9a0df4" />

(ii) To find the LU Decomposition of a matrix

<img width="1225" height="317" alt="image" src="https://github.com/user-attachments/assets/70eba3f2-3283-4100-84d5-aa6efeb3ec69" />







## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

