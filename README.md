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
# Register No:212223240009
# Developed By:ANTONY ABISHEK K
# 1-Norm of a Matrix:

import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,1)
print(f"{two_matrix:.2f}")

# 2-Norm of a Matrix
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print(f"{two_matrix:.2f}")

# Infinity Norm of a Matrix
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,np.inf)
print(f"{two_matrix:.2f}")

## Output:
### 1-Norm of a Matrix
![EX NO 7 AI 1](https://github.com/Antonyabishek2004/Norm-of-a-matrix/assets/138849620/8c52f89d-16a0-4a48-9063-44f5ec0d0bed)

### 2-Norm of a Matrix
![EX NO 7 AI 2](https://github.com/Antonyabishek2004/Norm-of-a-matrix/assets/138849620/16344bfb-5e70-4e34-8db1-cbc8d38dfa38)


### Infinity Norm of a Matrix
![EX NO 7 AI 3](https://github.com/Antonyabishek2004/Norm-of-a-matrix/assets/138849620/9102a005-bd7e-46f2-bfa9-a6a0051b54a6)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
