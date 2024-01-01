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
# Program to find 1-norm of a matrix.
# Developed by: THARUN D
# RegisterNumber: 212223240167
~~~
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm = "{:.2f}".format(ans)
print(Norm)
~~~

# 2-Norm of a Matrix

# Program to find 2-norm of a matrix.
# Developed by: THARUN D
# RegisterNumber: 212223240167
~~~
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm = "{:.2f}".format(ans)
print(Norm)
~~~
# Infinity Norm of a Matrix
# Program to find Infinity norm of a matrix.
# Developed by: THARUN D
# RegisterNumber: 212223240167
~~~
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm = "{:.2f}".format(ans)
print(Norm)
~~~

## Output:
![Screenshot 2024-01-01 121010](https://github.com/THARUNDT/Norm-of-a-matrix/assets/144871537/932df537-6bbf-4036-bff4-b63f329c1b26)
![Screenshot 2024-01-01 121018](https://github.com/THARUNDT/Norm-of-a-matrix/assets/144871537/03dc877b-4d56-4143-bd5d-a0188c7a6df1)
![Screenshot 2024-01-01 121027](https://github.com/THARUNDT/Norm-of-a-matrix/assets/144871537/2f1adea4-9a37-47ea-a554-05748f6add40)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
