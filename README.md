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
```Pyth
# Register No: 212225230046
# Developed By: R.DEEPIKA
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np
mat =np.array(eval(input())) 
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix
import numpy as np
mat =np.array(eval(input()))  
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans) 
print(Norm_of_matrix)


```
## Output:
### 1-Norm of a Matrix
<img width="1283" height="865" alt="Screenshot 2026-02-12 134520" src="https://github.com/user-attachments/assets/e12888c3-a1e6-4ce1-8783-4eaeb067fee5" />


### 2-Norm of a Matrix
<img width="1334" height="881" alt="Screenshot 2026-02-12 134538" src="https://github.com/user-attachments/assets/2de38873-006a-4078-a3ee-3d728d0a1734" />


### Infinity Norm of a Matrix
<img width="1279" height="863" alt="Screenshot 2026-02-12 134555" src="https://github.com/user-attachments/assets/8d28d635-3b09-4442-a64a-d3c257b92f70" />



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
