# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

Open vscode.
### Step 2:

Type the program.
### Step 3:

save the python file.
### Step 4:

create a text file .
### Step 5:

Run the program in the vscode, in the terminal type the following commands.
### Step 6:

End the program.

## PROGRAM:
```
#Developed by: S Santhosh
#Reference no: 22009296
import sys
count={}
a=sys.argv[1]
with open(a,'r') as f:
    for line in f:
        for word in line.split():
            if word not in count:
                count[word]=1
            else:
                count[word]+=1
print(count)
f.close()
```
### OUTPUT:



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
