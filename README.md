# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

create a file and add some content to it

### Step 2: 

open file using with keyboard/built-in function in read mode
 
### Step 3: 

use read() to read the contents of the file

### Step 4:  

split the lines using split().

### Step 5: 

iterate the list and increament the count.

### Step 6: 

print the output

## PROGRAM:
```
#program to find number of words
#developed by: jayavarthan
#register number: 22008689
fname = input('enter file name: ')
num_words = 0
with open(fname, 'r') as f:
for line in f:
words = line.split()
num_words += len(words)
print('number of words: ',num_words)
```
### OUTPUT:
![Screenshot_20230125_161831](https://user-images.githubusercontent.com/121369281/214783057-1e4920c7-0e0d-401f-ab8a-4bef86d2cb8d.png)

## RESULT:
Thus the program is written to find the word count from a text.
