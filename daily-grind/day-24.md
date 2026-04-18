# Day 24 - 🧮 Calculator Project: Full Build

## 🎯 Goal
Build a complete, working calculator with error handling.

## 🧠 Concept: Putting It All Together
Today you combine EVERYTHING you've learned:
- Functions
- Loops
- Conditionals
- User input
- Error handling

## 👨‍💻 The Full Calculator

```python
def add(a, b):
    return a + b

def subtract(a, b):
    return a - b

def multiply(a, b):
    return a * b

def divide(a, b):
    if b == 0:
        return "Error: Cannot divide by zero!"
    return a / b

def get_number(prompt):
    while True:
        try:
            return float(input(prompt))
        except ValueError:
            print("That's not a valid number. Try again.")

def calculator():
    print("=== Python Calculator ===")
    print("Operations: +, -, *, /")
    print("Type 'quit' to exit")
    print()

    while True:
        operation = input("Enter operation (+, -, *, /): ").strip()

        if operation == 'quit':
            print("Goodbye!")
            break

        if operation not in ['+', '-', '*', '/']:
            print("Invalid operation. Use +, -, *, or /")
            continue

        num1 = get_number("Enter first number: ")
        num2 = get_number("Enter second number: ")

        if operation == '+':
            result = add(num1, num2)
        elif operation == '-':
            result = subtract(num1, num2)
        elif operation == '*':
            result = multiply(num1, num2)
        elif operation == '/':
            result = divide(num1, num2)

        print(f"Result: {num1} {operation} {num2} = {result}")
        print()

main = calculator
main()
```

## 🧑‍💻 Your Task
1. Type out the FULL calculator program above
2. Run it and test several calculations
3. Test: what happens if you type a letter as a number?
4. Test: what happens if you divide by zero?

## 🌙 Extension Challenges
- Add a square root operation (%)
- Add a power/exponent operation (^)
- Track history of all calculations done in the session
- Add a "clear history" option

## 🔍 Prediction Task
Before running: if I type "abc" as the first number, what happens?

## 🧩 Reflection
> You just built your FIRST real project! What was the hardest part? What surprised you?
