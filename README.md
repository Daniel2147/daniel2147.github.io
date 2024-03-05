# daniel2147.github.io
```python
# Import the math library
import math

# Define a function to add two numbers
def add(a, b):
  return a + b

# Define a function to subtract two numbers
def subtract(a, b):
  return a - b

# Define a function to multiply two numbers
def multiply(a, b):
  return a * b

# Define a function to divide two numbers
def divide(a, b):
  return a / b

# Get the user's input for the first number
first_number = input("Enter the first number: ")

# Get the user's input for the second number
second_number = input("Enter the second number: ")

# Convert the user's input to numbers
first_number = int(first_number)
second_number = int(second_number)

# Choose the operation to perform
operation = input("Enter the operation to perform (+, -, *, /): ")

# Perform the operation
if operation == "+":
  result = add(first_number, second_number)
elif operation == "-":
  result = subtract(first_number, second_number)
elif operation == "*":
  result = multiply(first_number, second_number)
elif operation == "/":
  result = divide(first_number, second_number)

# Print the result
print("The result is:", result)
```
