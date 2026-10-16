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
## Program: <img width="674" height="420" alt="KK" src="https://github.com/user-attachments/assets/52d58a47-4f78-4333-b82d-74b4dbbe1703" />
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[1,3],[2,5]])
B=np.array([5,-3])
X=np.linalg.solve(A,B)
print (X)
## Output: <img width="397" height="132" alt="OK" src="https://github.com/user-attachments/assets/590d06e3-8827-4198-aca8-3505c27b7964" />
[-34.  13.]
## Result: 
Thus the solutions for the linear equations are successfully solved using python program

