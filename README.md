# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
### Step 2: 
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.JPG)
### Step 4: 
### Step 5: 
### PROGRAM:
#Program to find the distance between two points.
#Developed by: kamaleshwar.kv
#RegisterNumber:212223240063
import math
def calculate_distance(x1, y1, x2, y2):
    distance = math.sqrt((x2 - x1)**2 + (y2 - y1)**2)
    return round(distance, 2)
x1,y1 = 4, 2
x2,y2= 10, 6
bridge_length = calculate_distance(x1, y1,x2, y2)
print(f"{bridge_length}")


### OUTPUT:
![image](https://github.com/Kamaleshwa/DISTANCE-BETWEEN-TWO-POINTS/assets/144980199/8b1293cc-6254-40cc-a2d2-0b864b023ce3)


### RESULT:
