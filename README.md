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
# Register No:
# Developed By:
# 1-Norm of a Matrix
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Selva kumar A
RegisterNumber: 22009007
'''
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
![norm 1](https://user-images.githubusercontent.com/120643262/214851862-d4aa660d-2abc-4d6d-80df-d8659c2cdaf5.png)


### 2-Norm of a Matrix
![norm 2](https://user-images.githubusercontent.com/120643262/214851911-82af4e0b-940d-4847-8b26-15e30301cee2.png)


### Infinity Norm of a Matrix
![norm 3](https://user-images.githubusercontent.com/120643262/214852093-f9cddd78-56db-499f-9c04-c0941a4f61f4.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
