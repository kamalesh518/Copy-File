### Date:
# Ex-11:Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the file name and location from the user.

### Step 2:
Give a new file name to create a copy of a file content.

### Step 3:
Read the file and close the file.

### Step 4:
Now write the content in the new file.

### Step 5:
When done print"File copied successfully".

### Step 6:
End of the program
## PROGRAM:
```
'''Register no:24004024
Developed by: Kamalesh Y'''
def copy(text1,newfile):
    with open(text1) as fp:
        with open (newfile,'w') as fp1:
            data=fp.read()
            fp1.write(data)
copy("text1.txt","file2.txt")
```
### OUTPUT:
![image](https://github.com/user-attachments/assets/b26497c0-7696-4dcd-8bc5-8e9475e8faf3)

</br>

![image](https://github.com/user-attachments/assets/43fe68e2-b0e9-46dc-9950-b85c3fa9c32f)





## RESULT:
Thus the program is written to copy the contents from one file to another file.
