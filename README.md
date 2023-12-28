# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file.

### Step 2:
Write some lines in that file.

### Step 3:
Create a python file.

### Step 4:
Write a code to copy the content of the file to a new file.

### Step 5:
Run the program.

### Step 6:
Display the output.


## PROGRAM:
```
Developed By:A.Mandhakini
Register No: 23010115
```
~~~
def copy(filename,newfile):
    with open(filename,'r') as fp:
        with open(newfile,'w') as fp1:
            data1=fp.read()
            fp1.write(data1)
filename=input("Enter an Existing File:")
newfile=input("Enter a name for new file:")
copy(filename,newfile)
~~~
### OUTPUT:
![image](https://github.com/MandhakiniA/copy-file/assets/150005194/7eb2b4c8-13c6-441e-92eb-9f864b7fae3d)
![image](https://github.com/MandhakiniA/copy-file/assets/150005194/e65c87e1-1bd6-40ed-b816-233a359fc32e)





## RESULT:
Thus the program is written to copy the contents from one file to another file.
