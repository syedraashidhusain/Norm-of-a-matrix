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
# 1-Norm of a Matrix
```
# Register No: 212225040457
# Developed By: SYED RAASHID HUSAIN M
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"] = '1'
import numpy as np
matrix = eval(input())
one_matrix = np.linalg.norm(matrix,1)
print(f"{one_matrix:.2f}")
```

# 2-Norm of a Matrix
```
import os
os.environ["OPENBLAS_NUM_THREADS"] = '1'
'''
Program to find 2-norm of a matrix.
Register No: 212225040457
Developed By: SYED RAASHID HUSAIN M
'''
import numpy as np
matrix = eval(input())
two_matrix = np.linalg.norm(matrix,2)
print(f"{two_matrix:.2f}")
```

# Infinity Norm of a Matrix
```
import os
os.environ["OPENBLAS_NUM_THREADS"] = '1'
'''
Register No: 212225040457
Developed By: SYED RAASHID HUSAIN M
'''
import numpy as np
matrix = eval(input())
inf_matrix = np.linalg.norm(matrix,np.inf)
print(f"{inf_matrix:.2f}")
```

## Output:
### 1-Norm of a Matrix
<img width="1188" height="782" alt="image" src="https://github.com/user-attachments/assets/be34cf21-9efa-4445-983f-d463fd55bd52" />


<br>

### 2-Norm of a Matrix
<img width="1237" height="824" alt="image" src="https://github.com/user-attachments/assets/c71e14e1-124f-4129-bcc0-3b4179053492" />

<br>

### Infinity Norm of a Matrix
<img width="1235" height="778" alt="image" src="https://github.com/user-attachments/assets/1d0d1a50-a39f-483b-9db4-f1de23297994" />


<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
