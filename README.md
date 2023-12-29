# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

Import the sys.
### Step 2:

Open the file and assign it to data.
### Step 3:

Read the file and assign it to data.
### Step 4:

Split the data(data.split()).
### Step 5:

Print the word count by len(word).
### Step 6:

Close the file f1.
## PROGRAM:
```
'''
Developed by: SARAVANAN G
RegisterNumber: 23005445
'''
import sys
f1=open(sys.argv[0])
data=f1.read()
word=data.split()
print("The word count is",len(word))
f1.close()
```
### OUTPUT:

![image](https://github.com/Saravanan2512/command-line-arguments-to-count-word/assets/144979117/205246c1-aaf5-4587-b800-0a6e69a4d6a1)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
