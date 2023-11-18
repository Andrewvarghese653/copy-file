# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required the from which we need to copy the text.

### Step 2: 
Using keyword "with" to open the required file.


 
### Step 3: 
Again using the with keyword to open the empty file.

### Step 4:  
The empty file is open by using 'W' which is used to write only.

### Step 5: 
The for function is used to take each line from the main file.

### Step 6: 
Write() is used to write the lines of main file to the empty file or to the directed file.

## PROGRAM:
```python
with open("text.txt","r") as f1:
    data=f1.read()
with open("data.txt","w") as f2:
    f2.write(data)
```
##TEXT FILE:
```python
with open("text.txt",'w')as fp:
  fp.write("Hello World")
  fp.write("\nWelcome to Python")
  fp.write("\nHave a Good Day")
```
##EMPTY FILE:
```python
with open("data.txt","w") as fd:
 fd.write("")
```

### OUTPUT:
<img width="670" alt="Screenshot 2023-11-18 at 10 40 02 AM" src="https://github.com/Andrewvarghese653/copy-file/assets/145822115/4e7df950-74bf-44be-b41d-0da468786aa6">




## RESULT:
Thus the program is written to copy the contents from one file to another file.
