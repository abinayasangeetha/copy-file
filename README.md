# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 

## Step 1: Open the file f1 in read mode.
## Step 2: Open the file f2 in append mode.
## Step 3: Copy the contents using write() with the for loop.
## Step 4: End the program.


## PROGRAM:
```
#Developed By: ABINAYA S
#Register No: 212222230002
with open('f1.txt','r') as f1:
    with open ('f2.txt','a') as f2:
        for line in f1:
            f2.write(line)
```
### OUTPUT:
## Program
![program](https://github.com/abinayasangeetha/copy-file/assets/119393675/4c38af41-372f-4bce-8010-389598274394)
## File 1
![f1](https://github.com/abinayasangeetha/copy-file/assets/119393675/79bfe8ae-8e85-471c-ac1b-f5a27c35c4df)
## File 2
![f2](https://github.com/abinayasangeetha/copy-file/assets/119393675/e468bee7-b7cc-49e9-81a6-5e0a4ab5e62a)
## File 1 copied into File 2
![f2 txt](https://github.com/abinayasangeetha/copy-file/assets/119393675/b96ff4b8-78a7-4f2e-950e-87db05a4741c)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
