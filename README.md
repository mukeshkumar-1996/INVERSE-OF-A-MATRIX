## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Start the program
### Step 2: Import the necessary libraries(numpy,scipy.linalg)
### Step 3: Define the matrix using numpy
### Step 4: Use lu(),lu_solve(),lu_factor() to get the solutions
### step 5: End the program
## Program:
    #program to find the inverse of a matrix.
    #Developed by: Mukesh kumar.V
    #Register Number: 212225230193
    import os
    os.environ["OPENBLAS_NUM_THREADS"]="1"
    import numpy as np
    A = np.array([[6, 2, 3],
                  [3, 1, 1],
                  [10, 3, 4]])
    inverse = np.linalg.inv(A)


    print(inverse)
    
<img width="896" height="645" alt="Screenshot 2026-06-05 122936" src="https://github.com/user-attachments/assets/9583ba75-c9bf-4326-ad3d-13ff35d5d52a" />

## Output:

<img width="568" height="340" alt="Screenshot 2026-06-05 122944" src="https://github.com/user-attachments/assets/7726363c-0598-415c-a9c5-79e7ca97f7ff" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

