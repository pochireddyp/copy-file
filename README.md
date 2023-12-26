# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1: Use open function to open the file in which we want to copy from and access it in read mode.

Step 2: Read the file and store in a variable.

Step 3: Now create a new file in which we want to paste the content using write access mode.

Step 4: Use write function to copy the read file that has been stored in the variable.

Step 5: The content in the original file will be copied in the new file.

Step 6: End the program.

## PROGRAM:
```
#Devolped By:Masina Sree Karsh
#Ref no: 23005860
with open("text.txt","r") as f1:
    with open("copy.txt","w") as f2:
        line=f1.read()
        f2.write(line)
```
### OUTPUT:
![image](https://github.com/pochireddyp/copy-file/assets/150232043/aee3b26e-34ea-43d1-b1a5-8df791aed0c5)
![image](https://github.com/pochireddyp/copy-file/assets/150232043/9fac1d0b-724c-4544-b1b3-5f947052deee)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
