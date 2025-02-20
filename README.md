# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
Import sys module

## Step 2:
Open the file with sys.argv[1]

## Step 3:
Use the for loop to select the content in file

## Step 4:
Use split function to to separate the file content into words or strings

## Step 5:
Count the length of the words using len

## Step 6:
Print the number of words

## PROGRAM:
```
Program for getting the word count from the contents of a file using command line arguments
Developed by: Chandrasekar S
Register no: 212222230025
```
```
import sys
fp=open(sys.argv[1],'r')
d={}
for line in fp:
    for w in i.split():
        if w not in d.keys():
            d[w]-1
        else:
            d[w]+=1

print("Number of words in a file",count)
```

### OUTPUT:
![image](https://github.com/ChandrasekarS22008273/command-line-arguments-to-count-word/assets/119643845/f47194e4-e91b-48a5-b360-6456e7b7be4c)
![exp 5b 2](https://github.com/Safeeq-Fazil/command-line-arguments-to-count-word/assets/118680361/eae3274c-db7f-4a66-b5bf-e6b0c2fd525e)
![exp 5b 3](https://github.com/Safeeq-Fazil/command-line-arguments-to-count-word/assets/118680361/0de14d9f-08f3-4db3-8548-8b64e6eaf468)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
