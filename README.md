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
# Register No:212223230150
# Developed By: G. Pradeep Kumar

# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
<br>![Screenshot 2024-05-09 190923](https://github.com/pradeep23014186/Norm-of-a-matrix/assets/152294642/01c24f50-fddb-43bb-b334-aa22c20fb6e7)

<br>
<br>

### 2-Norm of a Matrix
<br>![Screenshot 2024-05-09 190943](https://github.com/pradeep23014186/Norm-of-a-matrix/assets/152294642/1066a038-7a15-427b-903f-748b0b048578)

<br>
<br>

### Infinity Norm of a Matrix
<br>![Screenshot 2024-05-09 190959](https://github.com/pradeep23014186/Norm-of-a-matrix/assets/152294642/fed31678-f6e8-40cb-b471-e786bbe5d6c3)

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
