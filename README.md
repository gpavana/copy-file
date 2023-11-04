# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file f1 in read mode.
### Step 2: 
Open the file f2 in append mode.
### Step 3: 
Copy the contents using write() with the for loop.
### Step 4:  
End the program.

## PROGRAM:
```
#Developed By: PAVANA G
#Register No: 212222230105
with open('f1.txt','r') as f1:
    with open ('f2.txt','a') as f2:
        for line in f1:
            f2.write(line)
```
### file1 content:
![Screenshot (237)](https://github.com/gpavana/copy-file/assets/118787343/be81293d-e2ca-4da7-8f83-557e53a2c1ca)

### file2 content:
![Screenshot (238)](https://github.com/gpavana/copy-file/assets/118787343/c1d1cc7d-95e2-4242-87e6-c2e43a744ec6)

### OUTPUT:
![Screenshot (236)](https://github.com/gpavana/copy-file/assets/118787343/4a82b8f0-0883-4a34-be0d-c8d9df6b49c7)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
