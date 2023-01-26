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
# Register No:22004035
# Developed By:PRAVEENKUMAR S
```
1-norm of matrix
import numpy as np 
mat = np.array(eval(input())) 
ans = np.linalg.norm(mat,1)
Norm_of_matrix ="{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
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
1-Norm of a Matrix

![norm1](https://user-images.githubusercontent.com/119559827/214849523-9cd6a935-f431-49c0-8792-60d00f83caf8.png)

2-Norm of a Matrix

![norm2](https://user-images.githubusercontent.com/119559827/214849783-86c86215-0575-4220-b3fc-7d6bcc294fb9.png)

3-Infinity Norm of a Matrix

![infinity norm](https://user-images.githubusercontent.com/119559827/214849987-ed9ee2ce-6eb3-4f9e-8487-889c95c6355f.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
