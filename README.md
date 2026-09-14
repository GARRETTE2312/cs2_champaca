# cs2_champaca

import math

# Ask user for the first point of x and y
x1 = float(input("Enter x1: "))
y1 = float(input("Enter y1: "))

# Ask user for the second point of x and y
x2 = float(input("Enter x2: "))
y2 = float(input("Enter y2: "))

# Calculate for the distance between two coordinates provided by the user
distance = math.sqrt(math.pow(x2 - x1, 2) + math.pow(y2 - y1, 2))

# Display the results of calculation
print(f"The distance between the two points is: {distance:.2f}")
