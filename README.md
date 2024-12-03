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
# Register No:24900699
# Developed By:NIKILA D
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

![Screenshot (38)](https://github.com/user-attachments/assets/9cce4c2c-9401-487d-87d2-fba8606015dc)

### 2-Norm of a Matrix

![Screenshot (39)](https://github.com/user-attachments/assets/3a467466-ca0d-4b86-b321-4c1ae137da80)

### Infinity Norm of a Matrix

![Screenshot (40)](https://github.com/user-attachments/assets/a214c935-4682-4d82-84cc-fddab369f3ae)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
