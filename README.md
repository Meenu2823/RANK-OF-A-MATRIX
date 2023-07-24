# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Start the program by importing numpy module as np for doing calculations using the builtin functions
### Step 2: Assign the given matrix to a variable using the command np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Print the result and end the program
## Program:
~~~
#Program to find the rank of a matrix.
#Developed by: Meenu.S
#RegisterNumber:23003303
import numpy as np
a=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
result=np.linalg.matrix_rank(a)
print(result)
~~~
## Output:
![Alt text](<Maths Exp-02.png>)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

