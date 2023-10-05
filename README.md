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
# Register No: 212222110048
# Developed By: SUDHARSAN RAM M

# 1-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
ans=np.linalg.norm(a,1)
print("{:.2f}".format(ans))




# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: SUDHARSAN RAM M 
RegisterNumber: 212222110048
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))



# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))



```
## Output:
### 1-Norm of a Matrix
![mat 7a](https://github.com/Sudharsanram/Norm-of-a-matrix/assets/119393980/9a367d3c-8684-4340-b20a-48ae9bb0996c)


### 2-Norm of a Matrix
![mat 7b](https://github.com/Sudharsanram/Norm-of-a-matrix/assets/119393980/13ba55ac-b84c-4143-b2f9-bd7303fe0598)


### Infinity Norm of a Matrix
![mat 7c](https://github.com/Sudharsanram/Norm-of-a-matrix/assets/119393980/768e13cb-d280-4b85-b58c-57e3a9fcaf92)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
