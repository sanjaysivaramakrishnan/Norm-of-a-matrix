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
# Register No: 23013798
# Developed By: Sanjay sivaramakrishnan M
# 1-Norm of a Matrix

import numpy as np

a=np.array(eval(input()))
x=np.linalg.norm(a,1)
x=float(x)
print("{:.2f}".format(x))



# 2-Norm of a Matrix
import numpy as np

a=np.array(eval(input()))
x=np.linalg.norm(a,2)
x=float(x)
print("{:.2f}".format(x))




# Infinity Norm of a Matrix
import numpy as np

a=np.array(eval(input()))
x=np.linalg.norm(a,np.inf)
x=float(x)
print("{:.2f}".format(x))





```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/sanjaysivaramakrishnan/Norm-of-a-matrix/assets/151629616/92157ed9-a50f-446d-ac90-962a14cfd70d)

### 2-Norm of a Matrix
![image](https://github.com/sanjaysivaramakrishnan/Norm-of-a-matrix/assets/151629616/e33d414f-6f4e-4c47-b570-54d45a2d0395)

### Infinity Norm of a Matrix
![image](https://github.com/sanjaysivaramakrishnan/Norm-of-a-matrix/assets/151629616/419c8f01-cac6-48ac-bb00-e7e6d914cb26)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
