# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

	1. Get the input matrix using np.array() 
	2. Compute 1-norm using np.linalg.norm(A, 1)
    3. Find the 2-norm of the matrix using np.linalg.norm()
	4. Compute infinity norm using np.linalg.norm(A, np.inf)
	5. Print the norm of the matrix in two decimal places.
	
## Program:
```Python
# Register No: 212225040113
# Developed By: V. HARINI

# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)


# 2-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
<img width="572" height="202" alt="image" src="https://github.com/user-attachments/assets/cd1d8c5e-548d-491f-8b08-d05686aff513" />


### 2-Norm of a Matrix
<img width="506" height="247" alt="image" src="https://github.com/user-attachments/assets/27b89b5d-630c-46b8-a77d-c74a80ff39ae" />


### Infinity Norm of a Matrix
<img width="562" height="199" alt="image" src="https://github.com/user-attachments/assets/7cc88b7b-adbe-4bda-955e-ef1179566aa6" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
