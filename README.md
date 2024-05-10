# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import numpy as np
### Step 2: 
Enter the input values
### Step 3: 
Write python program for getting the word count from the contents of a file using command line arguments
### Step 4:  
Run the program
### Step 5: 
Input the values
### Step 6: 
End the program
## PROGRAM:
```
# program to find the number of words in a text file
# Developed by : RITHVIK S 
# Register number : 212223100045
num=0
with open("story.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)
```             
### OUTPUT:
![328072258-84afc0ec-3137-49ce-b2f9-d4686031bd94](https://github.com/Rithviknathan/Word-Count/assets/148410509/172b286f-7fbc-490d-92e5-4712a40e57ce)
## RESULT:
Thus the program is written to find the word count from a text.
