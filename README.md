# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: First import sys.

### Step 2:  Keep the variable count as empty.
 
### Step 3: Open the file and access the file in reading mode.

### Step 4:  Iterate the loop using for loop in line.split().

### Step 5: Using if condition increment the value.

### Step 6: Print the variable count and close the file.

## PROGRAM:
```
Program developed by: Sri Sai Priya.S
Reference number: 22006141
Python program for getting the word count from the contents of a file using command line arguments.

import sys
d={}
f=open(sys.argv[1],"r")
for line in f:
    l=line.split(" ")
    for word in l:
        if word not in d:
           d[word]=1
        else:
           d[word]+=1
print(d)
f.close()
```

### OUTPUT:
![output](/Screenshot%20from%202023-01-27%2011-50-30.png)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
