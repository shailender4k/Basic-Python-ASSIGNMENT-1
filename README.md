# Take two numbers as input from the user
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

# Perform arithmetic operations
sum = num1 + num2
difference = num1 - num2
product = num1 * num2
division = num1 / num2 if num2 != 0 else "Undefined (division by zero)"

# Display results
print(f"\nSum: {num1} + {num2} = {sum}")
print(f"Difference: {num1} - {num2} = {difference}")
print(f"Product: {num1} * {num2} = {product}")
print(f"Division: {num1} / {num2} = {division}")
