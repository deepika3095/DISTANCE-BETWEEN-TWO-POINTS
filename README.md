# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Analyse the question
### Step 2: 
Find the algorithm to solve
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.JPG)
### Step 4: 
Execute the code
### Step 5: 
Obtain the output
### PROGRAM:
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
![Screenshot (74)](https://github.com/user-attachments/assets/91d3b904-3d83-49c7-a6f6-9242e39aea67)

### RESULT:
The distacnce between two points found successfully.
