# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text file in a specific loaction of interest
### Step 2: 
On the same location as the text file, create a python program file. 
### Step 3: 
In python Program, import sys and open a text file with argument "sys.argv[1]"
### Step 4:  
using read() and split(), split the lines in the file into a sequence of words
### Step 5: 
using len() count the number of words in the text file
### Step 6: 
In command prompt, initiate python followed by program name and text file name to get the output
## PROGRAM:
```
python program for getting the word count from the contents of a file using command line arguments.
'''
Develpoed By: Kolluru Pujitha
RegisterNumber: 23002983
'''
import sys
fp=open(sys.argv[1])
data=fp.read()
words=data.split()
print("no of words",len(words))
```
### OUTPUT:
![image](https://github.com/KolluruPujitha/command-line-arguments-to-count-word/assets/150231340/649837f0-eef0-46de-9192-6a87a2a7c0d7)

![image](https://github.com/KolluruPujitha/command-line-arguments-to-count-word/assets/150231340/b6ac7f91-f0b7-45c4-81c2-96f995aca5ed)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
