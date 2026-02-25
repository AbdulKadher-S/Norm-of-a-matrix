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
# Register No:212225230002
# Developed By:Abdul Kadher S
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
<img width="1249" height="699" alt="AdobeExpressPhotos_3813423e9a8c414ca7804ccc1974268c_CopyEdited" src="https://github.com/user-attachments/assets/f7ccc456-0e60-450e-841f-1837dd930f9f" />


### 2-Norm of a Matrix
<img width="1224" height="730" alt="AdobeExpressPhotos_9286a9e03ab94ecf889afa2dbcde9d0b_CopyEdited" src="https://github.com/user-attachments/assets/95bab237-c8f3-45b6-9fb1-e89d240222f1" />


### Infinity Norm of a Matrix
<img width="1227" height="701" alt="AdobeExpressPhotos_8caa69991ba049b28b788adf47f9dd34_CopyEdited" src="https://github.com/user-attachments/assets/36bd81eb-f332-4084-b57e-9a0428d4670f" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
