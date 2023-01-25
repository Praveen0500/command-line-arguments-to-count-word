# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys

### Step 2:
Initially make count = 0

### Step 3:
Open the content file using command line arguments.

### Step 4:
By using for loop name the function as "line"

### Step 5:
Split the line using .split

### Step 6:
Count the length of the word and print it

## PROGRAM:
```
'''
#Develeped by: Praveen s
#Register number : 22009060
'''

import sys
count=0
with open(sys.argv[1],'r') as f:
        for line in f:
            word=line.split()
            count+=len(word)
print("Word Count in File=",count)
```
### OUTPUT:


![5b pic (1)](https://user-images.githubusercontent.com/120218611/214647455-cf626b4a-b7be-49f0-8c97-b871f0c77f17.png)

![PRA 5B](https://user-images.githubusercontent.com/120218611/214647488-907c587b-06c7-4efc-a192-2ccc31b1da58.png)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
