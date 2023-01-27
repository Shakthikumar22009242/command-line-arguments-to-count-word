# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys
### Step 2: 
Open the file by using keyword open().
### Step 3: 
Using for loop in f1.
### Step 4:  
Count the number of words by keyword len.
### Step 5: 
Print the count.
### Step 6: 
End the Program
## PROGRAM:
```python
# Developed by: Shakthi Kumar S
# Ref no : 22009242
import sys
count = 0
with open(sys.argv[1],'r')as f1:
    for line in f1:
        word = line.split()
        count += len(word)
print("word count in file = ",count)
```
### OUTPUT:
![](Command%20line%201.png)
![](command%20line%202.png)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
