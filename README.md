# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 

Assign the coordinates of the first point (x1, y1) and the second point (x2, y2).

### Step 2: 

Calculate the difference between the x-coordinates of the two points and  between y coordinates of two points

### Step 3: 

Substitute the values in the distance formula  ![formula](/formula.JPG)

### Step 4: 

The distance variable now contains the calculated distance between the two points.

### Step 5: 

print it

### PROGRAM:
  
    #Program to find the distance between two points.
    #Developed by: VINODHINI. K
    #RegisterNumber:23013556
    import math
    x1,y1=4,2
    x2,y2=10,6
    distance=math.sqrt((x2-x1)**2+(y2-y1)**2)
    print(round(distance,2))
### OUTPUT:

![Alt text](<Screenshot 2023-11-28 221943.png>)

### RESULT:

Thus the distance between two points are successfully executed.