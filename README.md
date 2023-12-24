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
# Register No:23010231
# Developed By: SHRUTHI D.N

# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_matrix="{:.2f}".format(ans)
print(norm_matrix)

# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_matrix="{:.2f}".format(ans)
print(norm_matrix)

# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_matrix="{:.2f}".format(ans)
print(norm_matrix)
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Shruthidn27/Norm-of-a-matrix/assets/138849783/93c0dbff-202f-4fd9-993a-9c13df124a08)

### 2-Norm of a Matrix
![image](https://github.com/Shruthidn27/Norm-of-a-matrix/assets/138849783/e9377c8b-6936-4e46-a6f5-0fd9890c6555)

### Infinity Norm of a Matrix
![image](https://github.com/Shruthidn27/Norm-of-a-matrix/assets/138849783/714a654a-e6cb-4131-8e2c-d1b4e1e7205d)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
