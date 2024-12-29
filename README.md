# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## 1-Norm :
	1. Import numpy as np.
	2. Use np.array() to convert the evaluated input into a NumPy array.
	3. Compute the 1-norm using np.linalg.norm() with ord=1.
	4. Print the result using print().
## 2-Norm :
	1. Import numpy as np.
	2. Use np.array() to convert the evaluated input into a NumPy array.
	3. Compute the 2-norm using np.linalg.norm() with ord2.
	4. Print the result using print().
## Infinity-Norm:
	1. Import numpy as np.
	2. Use np.array() to convert the evaluated input into a NumPy array.
	3. Compute the Infinity-norm using np.linalg.norm() with "np.inf"
	4. Print the result using print().
## Program:
```
# Register No: 24901150
# Developed By: AKASH CT
```
# 1-Norm of a Matrix
```
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,1)
print(result)
```
# 2-Norm of a Matrix
```
import numpy as np
mat=(eval(input()))
ah=np.linalg.norm(mat,2)
print(f"{ah:.2f}")
```
# Infinity Norm of a Matrix
```
import numpy as np
a=eval(input())
ar=np.array(a)
ah=np.linalg.norm(ar,np.inf)
print(ah)
```
## Output:
### 1-Norm of a Matrix
![alt text](image-2.png)
### 2-Norm of a Matrix
![OUTPUT](image-1.png)
### Infinity Norm of a Matrix
![oUTPUT](image.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
