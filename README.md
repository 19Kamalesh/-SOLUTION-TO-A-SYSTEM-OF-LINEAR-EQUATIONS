# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by: D R NETHRANJAN CHOWDARY
#RegisterNumber:212225100031
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np 
matrixA=np.array([[1,3],[2,5]])
constants=np.array([5,-3])
result=np.linalg.solve(matrixA,constants)
print(result)
```

## Output:
<img width="1493" height="811" alt="image" src="https://github.com/user-attachments/assets/43884799-d33a-42c8-8284-307636883253" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

