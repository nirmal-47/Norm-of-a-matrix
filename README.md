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
1.
```
'''Nirmal.M
212225040282'''

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
```
Program to find 2-norm of a matrix.
Developed by:Nirmal.M
RegisterNumber: 212225040282
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
3.
```
'''Nirmal.M
212225040282'''
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```

## Output:
`###1.
<img width="635" height="214" alt="{389AEBCF-58AB-40D1-AEEB-BD63C06956EE}" src="https://github.com/user-attachments/assets/4f5f18b4-0805-4304-812a-bd6671f4b5b1" />


### 2.

<img width="484" height="228" alt="{E4F72BFB-E528-4AD1-878B-AC9EA3CE48FE}" src="https://github.com/user-attachments/assets/04c87cc8-a38b-440d-bf47-df90137cedba" />

### 3.
<img width="664" height="193" alt="{A0434177-EB51-4DA9-9F05-E4A6A378923A}" src="https://github.com/user-attachments/assets/63e4dc9b-2ecd-4c39-8f52-aa8f6d7e8628" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
