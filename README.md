# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text file in a specific loaction of interest.
### Step 2: 
On the same location as the text file, create a python program file.
### Step 3: 
In python Program, import sys and open a text file with argument "sys.argv[1]"
### Step 4:  
Using read() and split(), split the lines in the file into a sequence of words.
### Step 5: 
sing len() count the number of words in the text file.
### Step 6: 
In command prompt, initiate python followed by program name and text file name to get the output.
## PROGRAM:
```
To develop a Python program for getting the word count from the contents of a file using command line arguments.
Develpoed By : Dhivya Shri.B
RegisterNumber : 21002377
import sys
f1=open(sys.argv[1])
data=f1.read()
word=data.split()
print("The word count is",len(word))
f1.close()
```

### OUTPUT:
Text File "File1.txt":
![image](https://user-images.githubusercontent.com/94505585/154468732-0f53ca69-9eb7-436d-bfdf-559def95e7af.png)
Command Powershell prompt:
![image](https://user-images.githubusercontent.com/94505585/154468788-e437fb2f-3e7c-44a6-b6a9-e697dc87514c.png)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
