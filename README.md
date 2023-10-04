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
# Register No: 212222230133
# Developed By: SARAVANA KUMAR M
# 1-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)

# 2-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,2)
norm="{:.2f}".format(soln)
print(norm)

# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(soln)
print(norm)
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-10-04 133323](https://github.com/Saravana-kumar369/Norm-of-a-matrix/assets/117925254/c23cbf61-388a-4016-a41f-9b6051d49ef0)

### 2-Norm of a Matrix
![Screenshot 2023-10-04 133408](https://github.com/Saravana-kumar369/Norm-of-a-matrix/assets/117925254/62fb96a4-63a6-437e-81f8-5c336fd1aeb2)

### Infinity Norm of a Matrix
![Screenshot 2023-10-04 133840](https://github.com/Saravana-kumar369/Norm-of-a-matrix/assets/117925254/bf8b83ad-4b58-4f07-b4db-7b7c6828c297)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
