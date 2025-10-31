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
# Register No:212224240148
# Developed By:shaik lahir
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by:shaiklahir
RegisterNumber:212224240148 
'''
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
<img width="1257" height="360" alt="image" src="https://github.com/user-attachments/assets/fefa9834-3a68-4f63-ab3c-b40da56feef6" />


### 2-Norm of a Matrix
<img width="1283" height="430" alt="image" src="https://github.com/user-attachments/assets/548f2384-3280-4064-9e43-48025f24a4c4" />


### Infinity Norm of a Matrix
<img width="1180" height="310" alt="image" src="https://github.com/user-attachments/assets/88889f34-d7a2-4228-8611-38e05a4eac13" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
