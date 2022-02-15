# Inverse-of-matrix

## AIM:
 To find the inverse of the matrix

## ALGORITHM:
### Step 1:
import numpy as np.
### Step 2:
Enter the input.
### Step 3:
Use for loop and range.
### Step 4:
Use np.linalg.inv() to find inver of a matrix
### Step 5:
print() 


## PROGRAM:
### DEVELOPED BY: SUBRAMANIYA PILLAI.B
### REFERENCE NUM: 21006076
```
import numpy as np
l1,l2 = [],[]
r,c= int(input()),int(input())
for i in range(r):
    for j in range(c):
        num=int(input())
        l1.append(num)
    l2.append(l1)
    l1=[]
print(l2)
value1= np.array(l2)
inverse = np.linalg.inv(value1)
print(inverse)
```

## OUTPUT:
![git](./1.jpeg)

## RESULT:
Thus the program is executed to find the inverse of the matrices.
