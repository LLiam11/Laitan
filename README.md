# Laitan
READMe
import math
 
# Ask the user for the coordinates
x(1) = float(input("Enter x1: "))
y(1) = float(input("Enter y1: "))
x(2) = float(input("Enter x2: "))
y(2) = float(input("Enter y2: "))

# Find the distance using sqrt() and pow()
distance = math.sqrt(math.pow(x(2) - x(1), 2) + math.pow(y(2) - y(1), 2))

# Display the distance
print(f"The distance between the two points is: {distance:.2f}")
