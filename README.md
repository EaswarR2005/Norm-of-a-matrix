# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program:
```
Python
# Register No: EASWAR R
# Developed By: 212223230053

# 1-Norm of a Matrix:
Program to find 1-norm of a matrix.
Developed by: EASWAR R
RegisterNumber: 212223230053
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))

# 2-Norm of a Matrix:
Program to find 2-norm of a matrix.
Developed by: EASWAR R
RegisterNumber: 212223230053
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))

# Infinity Norm of a Matrix:
Program to find infinity-norm of a matrix.
Developed by: EASWAR R
RegisterNumber: 212223230053
import numpy as np
matrix=eval(input())
infinity_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(infinity_matrix))
```
## Output:
### 1-Norm of a Matrix:
![image](https://github.com/EaswarR2005/Norm-of-a-matrix/assets/146931525/332d4685-be56-467e-a553-a30852701afc)

### 2-Norm of a Matrix:
![image](https://github.com/EaswarR2005/Norm-of-a-matrix/assets/146931525/39c6b7e0-d7e6-4894-83a7-aef371334cce)

### Infinity Norm of a Matrix:
![image](https://github.com/EaswarR2005/Norm-of-a-matrix/assets/146931525/932c7d31-c442-402b-94bd-416eb4940f7d)

## Result:
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
