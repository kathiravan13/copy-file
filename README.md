# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:Step 1:
Use open function to open the file in which we want to copy from and access it in read mode.

Step 2:
Read the file and store in a variable.

Step 3:
Now create a new file in which we want to paste the content using write access mode.

Step 4:
Use write function to copy the read file that has been stored in the variable.

Step 5:
The content in the original file will be copied in the new file.

Step 6:
End the program. 

## PROGRAM:
```
''' 
Program for copying the contents from one file to another file
Programmed By: kathiravan.p
RegisterNumber: 212222230063
'''
with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:



![5cccccccc](https://github.com/kathiravan13/copy-file/assets/119831303/49b62788-8423-4fd7-9245-7f0628f0fdd8)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
