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
# Register No: 212223230170
# Developed By: RANJANI A
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
![Screenshot (210)](https://github.com/Ranjania2005/Norm-of-a-matrix/assets/151624950/d9d94f8e-6c3b-454a-93c1-40b13700492b)

### 2-Norm of a Matrix
![Screenshot (211)](https://github.com/Ranjania2005/Norm-of-a-matrix/assets/151624950/87416741-6a1a-4088-884d-75dcb1391480)

### Infinity Norm of a Matrix
![Screenshot (212)](https://github.com/Ranjania2005/Norm-of-a-matrix/assets/151624950/7df6bf3a-1df9-4aea-ae5b-150987447316)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
