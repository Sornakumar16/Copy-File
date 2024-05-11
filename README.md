# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Define the function as copy with arguements as existing file name and new file name.
### Step 2: 
 Open the existing file to read.
### Step 3: 
Open the new file to write.
### Step 4:  
Copy the contents from existing file to new file.
### Step 5: 
Get the inputs from the user for existing file and new file. Call the function.
### Step 6: 
End the program.
## PROGRAM:
~~~
Write a python program for copying the contents from one file to another file.
Develop by: SORNA KUMAR S
Register no: 212223230210
with open("text.txt",'r') as fp:
    msg1=fp.read()
with open("copy.txt",'w') as fp1:
    fp1.write(msg1)
~~~

### OUTPUT:
![image](https://github.com/Sornakumar16/Copy-File/assets/138849327/19ab1ec9-6ad7-4a04-b8f6-1d5ddcf0dc9e)

![image](https://github.com/Sornakumar16/Copy-File/assets/138849327/f7a25553-ee14-4a83-a6e0-a8ddcff0d046)

![image](https://github.com/Sornakumar16/Copy-File/assets/138849327/85bfceb6-70d3-437a-9b51-096fac5c5d0b)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
