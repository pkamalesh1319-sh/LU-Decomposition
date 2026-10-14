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

'''Program to find L and U matrix using LU decomposition.

Developed by: KAMALESH P

RegisterNumber: 26014307

'''

import os

os.environ["OPENBLAS_NUM_THREADS"]="1"


import numpy as np

from scipy.linalg import lu

A=np.array(eval(input()),dtype=float)

P,L,U=lu(A)

print(L)

print(U)


(ii) To find the LU Decomposition of a matrix

'''

Program to solve a matrix using LU decomposition.

Developed by: KAMALESH P

RegisterNumber: 26014307

'''

#To print X matrix (solution to the equations)

import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

from scipy.linalg import lu_factor,lu_solve

a=eval(input())

b=eval(input())

l,p=lu_factor(a)

x=lu_solve((l,p),b)

print(x)

## Output:
![lu decomposition]()
### 5A INPUT
<img width="1190" height="834" alt="Screenshot 2026-10-14 091055" src="https://github.com/user-attachments/assets/5fe11c4e-3976-413f-812a-a1e4391efd91" />

### 5A OUTPUT
<img width="1273" height="587" alt="Screenshot 2026-10-14 091116" src="https://github.com/user-attachments/assets/d7931f95-9782-4100-92fa-37d3a149c0de" />

### 5B INPUT
<img width="1173" height="820" alt="Screenshot 2026-10-14 091135" src="https://github.com/user-attachments/assets/afc90d25-bca8-4722-bc9f-b6e968f827cb" />

### 5B OUTPUT
<img width="1272" height="342" alt="Screenshot 2026-10-14 091150" src="https://github.com/user-attachments/assets/0946a6e3-cfad-4da6-85d6-73c2c5739e5b" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

