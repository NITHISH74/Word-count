# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open visual Studio code.
### Step 2: 
 Create a file with .py extension.

### Step 3: 
Create a another file with .txt extension .


### Step 4:  
Enter some inputs (or) words in .txt file.


### Step 5: 
Enter the code with file name as excatly given in .txt extension.


### Step 6: 
Run the code to find out the number of words in the .txt file.


## PROGRAM:
```
# Developed by: NITHISHWAR S
# Reference no: 21002766
# To write a program for getting the word count from a file.
```
```
with open("text.txt",'r') as fp:
    count=0
    for data in fp:
        l=data.split()
        for i in l:
            count+=1
    print("No of words in the file",count)
```
### OUTPUT:


## RESULT:
Thus the program is written to find the word count from a text.
