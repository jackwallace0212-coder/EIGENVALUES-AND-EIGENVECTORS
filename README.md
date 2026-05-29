# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 :
Import the numpy module to use the built-in functions for calculation

Step 2:
Prepare the lists from each linear equations and assign in np.array()

Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4:
End the Program

## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

a = np.array([[-2, 2, -3],
              [2, 1, -6],
              [-1, -2, 0]])

eigen_values, eigen_vectors = np.linalg.eig(a)

print("Eigen values are", eigen_values, "and Eigen Vectors are", eigen_vectors)
```

## Output:
<img width="1286" height="332" alt="Screenshot 2026-05-29 084814" src="https://github.com/user-attachments/assets/b271bd5b-1661-45e8-a84b-3efde204f04c" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
