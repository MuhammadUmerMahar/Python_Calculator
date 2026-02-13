# Python_Calculator
try:
    a = int(input("Enter first number: "))
    b = int(input("Enter second number: "))
except ValueError:
    print("You entered invalid input! Please enter numbers only.")
else:
    print("Which function would you like to perform?")
    function = input("You can perform only (+,-,*,/): ")

    if function == "+":
        print("The answer is:", a + b)
    elif function == "-":
        print("The answer is:", a - b)
    elif function == "*":
        print("The answer is:", a * b)
    elif function == "/":
        print("The answer is:", a / b)
    else:
        print("Invalid operator. Please try again using (+, -, *, /).")

print("Wish you all the best. Have a nice day!")
