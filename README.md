# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
We have to initialise program using import numpy to perform mathematical calculation

### Step 2: 
The input from the user is stored in the variable a


### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 
End of the program


## Program:
    
    #Program to find the eigen values and eigen vectors.
    #Developed by: JANARTHANAN V K
    #RegisterNumber: 212222230051
    import numpy as np
    A=np.array([[2,2],[1,3]])
    values,vectors=np.linalg.eig(A)
    print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
    
## Output:

![Screenshot 2023-06-09 191853](https://github.com/Janarthanan2/EIGENVALUES-AND-EIGENVECTORS/assets/119393515/cdf6117b-4d61-42d9-927c-02bcb94e706e)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
