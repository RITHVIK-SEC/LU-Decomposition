# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: RITHVIK S 
RegisterNumber:25007057
import numpy as np
from scipy.linalg import lu
a = np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)

*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: RITHVIK S
RegisterNumber:25007067
import numpy as np
from scipy.linalg import lu_factor, lu_solve
a = np.array(eval(input()))
b = np.array(eval(input()))
lu,pivot=lu_factor(a)
x = lu_solve((lu,pivot), b)
print(x)

*/
```

## Output:
<img width="1178" height="435" alt="Screenshot 2025-10-21 122639" src="https://github.com/user-attachments/assets/66f4231b-07f8-4b47-9106-6c92b55b2226" />
<img width="861" height="195" alt="Screenshot 2025-10-21 122648" src="https://github.com/user-attachments/assets/a472f57d-35af-4474-b5a6-ffd49028c3d7" />


![lu decomposition]()


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

