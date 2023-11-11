# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text1.txt with some content in it
### Step 2: 
 Open the text1.txt file in read mode
### Step 3: 
Create a copy.txt file using write mode
### Step 4:  
Copy the content of text1.txt file to copy.txt using write function

## PROGRAM:
```
Program for copying the contents from one file to another file
Developed by: HARISH G
RegisterNumber: 23000630

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![244350424-7085f53a-cce3-4197-9cf0-4f74f5f83771](https://github.com/Harish2404lll/copy-file/assets/141472096/08dd5311-c652-44b7-8aec-f1696b891481)

![244350850-81956b81-bfd5-4854-a98e-86c76786fa61](https://github.com/Harish2404lll/copy-file/assets/141472096/2e6dc749-5679-4489-98e4-b3e964904cda)

![244350620-1cf2761a-049c-4492-851f-b855d94971fc](https://github.com/Harish2404lll/copy-file/assets/141472096/3a02c365-bda2-4bdd-a114-b164b67163bd)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
