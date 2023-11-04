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
![Uploading Screenshot (237).png…]()

### file2 content:
![Uploading Screenshot (238).png…]()

### OUTPUT:
![Uploading Screenshot (236).png…]()



## RESULT:
Thus the program is written to copy the contents from one file to another file.
