# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM:-
 
### Step 1:

Start.

### Step 2:

Open the first file in read mode appropriate method.
 
### Step 3: 

Open the second file in write mode by an appropriate method.

### Step 4: 

Look until a variable 'i' in the first file.so variable i propagates all over the content.

### Step 5:

Write the value of 'i' in the second file by following method.SecondName.write(i).

### Step 6: 

stop.

## PROGRAM:-
~~~

'''
Developed by: D.vishnu vardhan reddy
reference Number: 21005311
'''
with open('text','r') as file1:
    with open('text1','w') as file2:
        for i in file1:
            file2.write(i)

~~~

### OUTPUT:-

![OUTPUT](/file.copy/file1.png)

TEST CASE:-

![OUTPUT](/file.copy/fie2.png)
![OUTPUT](/file.copy/file3.png)




## RESULT:
Thus the program is written to copy the contents from one file to another file.