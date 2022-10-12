# Inverse-of-matrix

## AIM:
To write a python program to find the inverse of a nested array.
## ALGORITHM:
### Step 1:
Importing numpy module.
### Step 2:
Creating empty list named l1 and l2.
### Step 3:
Get input from user. Get rows and columns as input from user.
### Step 4:
Use nested list to append list .
### Step 5:
Print the inverse of the array using np.lingalg.inv .

## PROGRAM:
```python
To write a python program for inverse of matrix
Developed by: Adhithya.S
Register Number: 22005823
import numpy as np
l1,l2=[],[]
rows=int(input())
column=int(input())
for i in range(rows):
    for j in range(column):
        l1.append(int(input()))
    l2.append(l1)
    l1=[]
print(l2)
value=np.array(l2)
inverse=np.linalg.inv(value)
print(inverse)
```
## OUTPUT:
![output](/filename3.png)
## RESULT:
A python program to find the inverse of a nested array is written.