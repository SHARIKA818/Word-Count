# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import numpy as np
### Step 2: 
 enter the input values
### Step 3: 
write python program for getting the word count from contents of a file using command line argument
### Step 4:  
run the program
### Step 5: 
input the values
### Step 6: 
end the program
## PROGRAM:
```

# Word count in a Text file
# Developed by: SHARIKA.R
# Register number: 212223230204
num=0
with open ("story.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
    print("The number of words are in the file is",num)
```

### OUTPUT:
![Screenshot 2024-10-16 032501](https://github.com/user-attachments/assets/a8bdc0a4-2d7f-46b7-96de-b0b70d6cb1ee)
![Screenshot 2024-10-16 032513](https://github.com/user-attachments/assets/34813a54-539e-4867-a4ef-8cc11788a850)


## RESULT:
Thus the program is written to find the word count from a text.
