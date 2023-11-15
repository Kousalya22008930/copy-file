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
#Developed By: KOUSALYA A.
#Register No: 212222230068
with open('f11.txt','r') as f1:
    with open ('f12.txt','a') as f2:
        for line in f1:
            f2.write(line)
```
### OUTPUT:
### FILE1:
![image](https://github.com/Kousalya22008930/copy-file/assets/119389108/4703fd33-5326-4505-b9f8-0af2f941caa8)
### FILE2:
![image](https://github.com/Kousalya22008930/copy-file/assets/119389108/40e65b43-ab78-4948-9db5-8dd9917490be)
### FILE1 COPIED INTO FILE2:
![image](https://github.com/Kousalya22008930/copy-file/assets/119389108/d419a7ac-8777-46a2-9154-1ae96969233f)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
