# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :Import numpy as np 
### Step 2: Assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
#Program to find the eigen values and eigen vectors.    
#Developed by: K pavithra   
#RegisterNumber:212224240112   
import numpy as np   
a=np.array([[4,2],[2,4]])    
value,vector=np.linalg.eig(a)  
print("Eigen values are",value,"and","Eigen Vectors are",vector)
## Output:
![Screenshot 2025-03-02 150428](https://github.com/user-attachments/assets/92c6a3d0-556a-4fa5-8884-a296783a6497)
![Screenshot 2025-03-02 150444](https://github.com/user-attachments/assets/5f5f81bd-c72c-40e1-ae2c-2f5aecbc2a5a)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
