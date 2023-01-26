# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

Get the input text file name from the user to count the words in it.

### Step 2: 

Assigning a  variable num_words is 0.
 
### Step 3: 

Opening the text file which the user entered.

### Step 4:  

Split the words in the file using spaces between them using for loop.

### Step 5: 

num_words increases for every word in the loop iteration.

### Step 6: 

Print the Number of Words and end the program.

## PROGRAM:
```
Program to get the word count from a text. 

Developed by: SWETHA P
RegisterNumer:22008542

fname=input("Enter file name: ")
num_words=0
with open(fname,'r') as f:
    for line in f:
        words=line.split()
        num_words+=len(words)
print("Number of words: ",num_words) 
```
### OUTPUT:

![wordcountpy](https://user-images.githubusercontent.com/120623583/214792462-3e1cc81e-9e46-4853-b47b-70255c64b269.png)

## RESULT:
Thus the program is written to find the word count from a text.
