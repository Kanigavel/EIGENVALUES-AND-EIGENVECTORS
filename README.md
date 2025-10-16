# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Start the program.
### Step 2:
Import the NumPy library as np.
### Step 3: 
Create a square matrix using np.array().
## Step 4:
Calculate the eigenvalues and eigenvectors using np.linalg.eig().
## Step 5:
Display the eigenvalues and eigenvectors.
## Step 6:
Stop the program.
 


## Program:
~~~
import numpy as np
a= np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
~~~
 <img width="1123" height="618" alt="image" src="https://github.com/user-attachments/assets/26a32e41-7497-446d-99c1-3fdf3b6881b6" />
## Output:
<img width="1168" height="281" alt="image" src="https://github.com/user-attachments/assets/50fdaada-688b-4eae-8b51-7d4b0fb74c9d" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
