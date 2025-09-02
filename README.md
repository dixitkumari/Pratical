# Pratical
import cmath  # cmath handles complex numbers

# Input coefficients
a = float(input("Enter coefficient a: "))
b = float(input("Enter coefficient b: "))
c = float(input("Enter coefficient c: "))

# Calculate the discriminant
D = b**2 - 4*a*c

# Calculate the two roots
root1 = (-b + cmath.sqrt(D)) / (2*a)
root2 = (-b - cmath.sqrt(D)) / (2*a)

# Output the results
print(f"The roots of the equation are: {root1} and {root2}")
