# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Substitute the values in the distance formula  ![formula](./formula.pngs)
### Step 4: 
print using .format model
### Step 5: 
End the program.
### PROGRAM:
```
#Program to find the distance between two points.
#Developed by:D.Paul Andrew
#RegisterNumber:21500230
x1,x2=10,4
y1,y2=6,2
import math
value=math.sqrt((x2-x1)**2+(y2-y1)**2)
print("{:.2f}".format(value))
```

### OUTPUT:
![OUTPUT](./output.png)

### RESULT:
The distance between the two points is displayed sucessfully.