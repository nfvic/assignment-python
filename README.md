# assignment-python
# basic calculator program
# Simple Calculator

# Get user input
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))
action = input("Enter an action (+, -, *, /): ")

# Perform the operation
if action == '+':
    result = num1 + num2
    print(f"{num1} + {num2} = {result}")
elif action == '-':
    result = num1 - num2
    print(f"{num1} - {num2} = {result}")
elif action == '*':
    result = num1 * num2
    print(f"{num1} * {num2} = {result}")
elif action == '/':
    if num2 != 0:
        result = num1 / num2
        print(f"{num1} / {num2} = {result}")
    else:
        print("Error: Division by zero is not allowed.")
else:
    print("Invalid action . Please enter +, -, *, or /.")
# Output:
