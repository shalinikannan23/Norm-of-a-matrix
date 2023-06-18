# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs 2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
   	2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```python
# Register No:212222240095
# Developed By:shalini.k
# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)
# 2-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,2)
norm="{:.2f}".format(soln)
print(norm)
# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(soln)
print(norm)
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/shalinikannan23/Norm-of-a-matrix/assets/118656529/4de9d822-d879-4f14-ae63-7234307780b2)
### 2-Norm of a Matrix
![image](https://github.com/shalinikannan23/Norm-of-a-matrix/assets/118656529/7070fc6f-cf6d-49bf-aabe-11a2bd686645)
### Infinity Norm of a Matrix
![image](https://github.com/shalinikannan23/Norm-of-a-matrix/assets/118656529/edf5021f-0a7d-4e52-8d84-bc088f5d9900)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
