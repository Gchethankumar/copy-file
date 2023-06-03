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
''' 
Program for copying the contents from one file to another file
Programmed By: G.Chethan Kumar
RegisterNumber: 212222240022
'''
with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![Screenshot 2023-06-03 094123](https://github.com/Gchethankumar/copy-file/assets/118348224/9ff8c916-0d5d-4ec9-a3df-9cc709c51d55)

![Screenshot 2023-06-03 094106](https://github.com/Gchethankumar/copy-file/assets/118348224/a5c00f3d-d301-4239-916f-f278d3f1a7df)

![Screenshot 2023-06-03 094057](https://github.com/Gchethankumar/copy-file/assets/118348224/9c846f83-f1cb-4739-8737-bb59f01161d9)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
