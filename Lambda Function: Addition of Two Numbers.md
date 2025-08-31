# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
f = lambda a, b: a + b

x = int(input("Enter first number: "))
y = int(input("Enter second number: "))

print("Sum is:", f(x, y))

## Output
Enter first number: 10
Enter second number: 25
Sum is: 35

## Result
The program successfully uses a lambda function to add two numbers and display the result.
