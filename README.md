num_1 = int(input("Enter the first number: "))
num_2 = int(input("Enter the second number: "))
addition = "+"
subtraction = "-"
division = "/"
multiplication = "*"
operation = input("Choose an operator: ")
if operation == "+":
    result = num_1 + num_2
    print(result)
elif operation == "-":
    result = num_1 - num_2
    print(result)
elif operation == "/":
    result = num_1 / num_2
    print(result)
elif operation == "*":
    result = num_1 * num_2
    print(result)
