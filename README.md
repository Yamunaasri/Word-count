# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

### Step 2: 
 
### Step 3: 

### Step 4:  

### Step 5: 

### Step 6: 

## PROGRAM:
'''
Program to count the number of words in a file
Developed by: Yamunaassri T S
Register Number: 212222240117
'''
fp=input("Enter the file name:")
words=0
with open(fp,'r') as f:
  for line in f:
    word=line.split()
    words+=len(word)
print("Number of words:",words)
### OUTPUT:

![image](https://github.com/Yamunaasri/Word-count/assets/115707860/20f4eb88-71c9-42c6-88e7-ec051a47df65)


## RESULT:
Thus the program is written to find the word count from a text.
