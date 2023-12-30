# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

### Step 2: 
 
### Step 3: 

### Step 4:  

### Step 5: 

### Step 6: 

## PROGRAM:
```python
try:
    with open("data_file.txt", 'r') as source:
        content = source.read()

    with open("output.txt", 'w') as destination:
        destination.write(content)

    print("File copied successfully!")
    
    with open("output.txt",'r') as fp:
        data = fp.read()
        
    print(f"Copied content:\n{data}")

except FileNotFoundError:
    print("One or both files not found.")
except Exception as e:
    print(f"An error occurred: {str(e)}")
```
### OUTPUT:
![image](https://github.com/SANTHAN-2006/copy-file/assets/80164014/1e16571d-4da1-486e-944e-72e6b8f201f7)
<br>
![image](https://github.com/SANTHAN-2006/copy-file/assets/80164014/fc4bd1aa-2bbd-4a15-9c43-ef584e42c0cb)
<br>
![image](https://github.com/SANTHAN-2006/copy-file/assets/80164014/c4b1290d-6ce9-4358-bc8a-19db5b8ad5b8)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
