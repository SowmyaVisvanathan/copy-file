# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the first file in read mode.
### Step 2: 
Open the second file in append mode
### Step 3: 
Every word in the first file is copied to second file using write()
### Step 4:  
Close the first file.
### Step 5: 
Close the second file.

## PROGRAM:
```
with open('doc1','r') as firstfile:
    with open('doc3', 'a') as secondfile:
        for line in firstfile: 
            secondfile.write(line)
```
### OUTPUT:
![output](/out3.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file.