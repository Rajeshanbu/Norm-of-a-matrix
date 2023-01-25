# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### 1. Get the input matrix using np.array()   
### 2. Find the 2-norm of the matrix using np.linalg.norm()
###	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:Rajesh A
# Developed By:22008551
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
 
# 2-Norm of a Matrix
'''python
Program to find 2-norm of a matrix.
Developed by:Rajesh A
RegisterNumber:22008551
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![norm 1](https://user-images.githubusercontent.com/118924713/214556605-9e8402ad-bcb2-4fec-8afd-c97b5a36ebbd.png)


### 2-Norm of a Matrix

![norm 2](https://user-images.githubusercontent.com/118924713/214556629-ecf6d7fb-c00d-439f-9094-4f4ea482cfc1.png)

### Infinity Norm of a Matrix
![norm 3](https://user-images.githubusercontent.com/118924713/214556654-e7fc910b-53d7-45ec-8016-c5f1a69107a1.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
