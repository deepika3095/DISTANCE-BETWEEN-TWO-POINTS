# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Get input from the user
### Step 2: 
Apply the format
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.JPG)
### Step 4: 
Execute the program 
### Step 5: 
Obtain the result
### PROGRAM:
  Developed by:DEEPIKA R
  212223230038

import math
def dis(x1,x2,y1,y2):
    d=((x2-x1)**2+(y2-y1)**2) 
    g=math.sqrt(d)
    return g
x1=4
x2=10
y1=2
y2=6
g=dis(x1,x2,y1,y2)
print("{:.2f}".format(g))


### OUTPUT:
![Screenshot (74)](https://github.com/user-attachments/assets/5e71a25e-728c-4c70-af8b-460d076fa443)


### RESULT:
Hence, the distance between two points is successfully found.
