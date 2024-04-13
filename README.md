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
```Python
# Register No:
# Developed By:
# 1-Norm of a Matrix
'''
Program to find the norm of a matrix
Developed by: Devadhaarini.D
Register no.:212223230040
'''
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))

# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Devadhaarini.D
RegisterNumber: 212223230040
'''
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))

# Infinity Norm of a Matrix
'''
Program to find the infinity norm of the given matrix
Developed by: Devadhaarini.D
Register no.:212223230040
'''
import numpy as np
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-04-13 212127](https://github.com/Devadhaarini/Norm-of-a-matrix/assets/145796552/72180cab-8876-40eb-bca9-5fd3b956019f)

### 2-Norm of a Matrix
![Screenshot 2024-04-13 212144](https://github.com/Devadhaarini/Norm-of-a-matrix/assets/145796552/5d6e1238-9d58-4722-98a3-d5baab94ad02)

### Infinity Norm of a Matrix
![Screenshot 2024-04-13 212156](https://github.com/Devadhaarini/Norm-of-a-matrix/assets/145796552/7dca7e9d-0d45-4d25-8701-3008b3b2017a)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
