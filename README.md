# DATE
# EX-07 Norm of a matrix
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
```
# Register No:BHUVANESHWARI M
# Developed By:212223230033
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-09-24 200607](https://github.com/user-attachments/assets/5c89a460-c241-438a-9592-14487a1caf13)


### 2-Norm of a Matrix
![Screenshot 2024-09-24 200624](https://github.com/user-attachments/assets/833fa1b3-0221-423a-aafc-9d43d112a77c)


### Infinity Norm of a Matrix
![Screenshot 2024-09-24 200637](https://github.com/user-attachments/assets/1afa8a90-debd-43bb-a3bc-36136fd162ba)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
