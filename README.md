
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
# Register No: 212225240133
# Developed By: SAKTHIVEKL K

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

<img width="1043" height="176" alt="image" src="https://github.com/user-attachments/assets/dc0f53f3-122a-46f5-b17d-c2bb8703323e" />

### 2-Norm of a Matrix

<img width="1043" height="222" alt="image" src="https://github.com/user-attachments/assets/171bb6a9-78fb-4ca4-a479-4b9fa8de87f4" />

### Infinity Norm of a Matrix

<img width="981" height="174" alt="image" src="https://github.com/user-attachments/assets/0df767a0-5923-4ed5-bc7d-67ccda5da9ea" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
