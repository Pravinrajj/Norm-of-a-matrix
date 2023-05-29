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
# Register No: 212222240080
# Developed By: Pravinrajj G.K
# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
print("%.2f"%soln)

# 2-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,2)
print("%.2f"%soln)

# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,np.inf)
print("%.2f"%soln)

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Pravinrajj/Norm-of-a-matrix/assets/117917674/d26f1731-f899-4e2e-8377-47c45f492167)

### 2-Norm of a Matrix
![image](https://github.com/Pravinrajj/Norm-of-a-matrix/assets/117917674/6ebe1c94-7045-458a-bce8-694e7b13d222)

### Infinity Norm of a Matrix
![image](https://github.com/Pravinrajj/Norm-of-a-matrix/assets/117917674/cf93889b-d325-43a4-b184-42c1a28d8370)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
