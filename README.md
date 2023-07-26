# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Prompt the user to enter the name of the file they want to analyze for word count

### Step 2: Initialize a variable to store the total word count and open the specified file in read mode.
 
### Step 3: Iterate through each line in the file using a loop and split the line into words using the split() method.

### Step 4: Add the number of words in each line to the word count variable using the len() function.

### Step 5: Repeat the process for all lines in the file until the end of the file is reached.

### Step 6: Print the final word count of the text file after the loop ends, thereby completing the Python program for word counting.

## PROGRAM:
```
# Program to count the no. of words in a file.
# Developed by: ponguru aasrith sairam
# Reg.no: 23007809
fname=input("Enter the file name:")
num_words=0
with open(fname,"r") as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
  print("Number of words:",num_words)
```

### OUTPUT:
![image](https://github.com/AasrithSairam/Word-count/assets/139331438/e3dbee50-2811-4325-8fec-5c3007acc8c2)



## RESULT:
Thus the program is written to find the word count from a text.
