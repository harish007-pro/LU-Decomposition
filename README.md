# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
# Step 1 :import numpy as np
# Step 2 :from scipy.linalg import lu
# Step 3 :print(L)
# Step 4 :print(U)
## Program:
    '''Program to find L and U matrix using LU decomposition.
    Developed by: Harish  G
    RegisterNumber: 24006523
    '''
    import numpy as np
    from scipy.linalg import lu
    A=np.array(eval(input()))
    P,L,U=lu(A)
    print(L)
    print(U)

## Output:
![alt text](<Screenshot 2024-12-10 085645.png>)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
