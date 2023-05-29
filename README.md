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
# Register No:212222240010
# Developed By:S.ANUSHARON
# 1-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)



# 2-Norm of a Matrix

import numpy as np
arr=np.array(eval(input()))
n=np.linalg.norm(arr,2)
print("{:.2f}".format(n))


# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
nor_of_matrix="{:.2f}".format(ans)
print(nor_of_matrix)




```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>

![Screenshot (81)](https://github.com/Anusharonselva/Norm-of-a-matrix/assets/119405600/59ab33f7-9770-4c31-aa9e-562505b5b81a)

### 2-Norm of a Matrix
<br>
<br>
<br>
![Screenshot (82)](https://github.com/Anusharonselva/Norm-of-a-matrix/assets/119405600/e80ccd8c-39a9-4bff-a180-0cbd05405a12)


### Infinity Norm of a Matrix
<br>
<br>
<br>
![Screenshot (87)](https://github.com/Anusharonselva/Norm-of-a-matrix/assets/119405600/6f7341fc-5564-4dcb-bca5-b6ad6be36c93)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
