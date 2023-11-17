# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
ALGORITHM:
Step 1:Import sys module
Step 2: Open the file with sys.argv[1]
Step 3: Use the for loop to select the content in file
Step 4: Use split function to to separate the file content into words or strings
Step 5: Count the length of the words using len
Step 6: Print the number of words

## PROGRAM:
Program for getting the word count from the contents of a file using command line arguments
Developed by: HARI PRASATH S
RegisterNumber: 212222240034

import sys
fp=open(sys.argv[1], 'r')
count=0
for line in fp:
    list1=line.split()
    count+=len(list1)
print("No of words in a file",count)

### OUTPUT:
![282795646-bd7282d1-0d9c-4dda-95b9-880dc469bef0](https://github.com/hariprasath5106/command-line-arguments-to-count-word/assets/111515488/300e6aa5-d704-4e70-8fbb-861b97a9dd7e)
![282795681-85002f07-ef5e-4094-9316-0267e4c06066](https://github.com/hariprasath5106/command-line-arguments-to-count-word/assets/111515488/1cf10502-da2b-495c-8c52-7a917c865914)
![282795697-edbdb2f7-25e2-4d75-a488-95861c35cc78](https://github.com/hariprasath5106/command-line-arguments-to-count-word/assets/111515488/160aeba0-d4f0-437b-8298-becd62a9cb4f)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
