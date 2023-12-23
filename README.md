# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import the sys module.

### Step 2:
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]

### Step 3:
Read the file using read() method.

### Step 4:
Use split() method to split the file content into words.

### Step 5:
Use len() to find the total words.

### Step 6:
Run the program to determine the number of words in the file created.

## PROGRAM:
```
Developed by : A.Lahari
Registered number : 212223230111

import sys
file= open(sys.argv[1])
data=file.read()
words=data.split()
print("Total Words:",len(words))

```
### OUTPUT:

![image](https://github.com/AkilaMohan/command-line-arguments-to-count-word/assets/139842204/83901d37-bfa0-4d75-b20b-77d7b077cc38)
![image](https://github.com/AkilaMohan/command-line-arguments-to-count-word/assets/139842204/7c8d3335-9e14-41db-a45e-47845c1a14c8)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
