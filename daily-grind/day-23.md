# Day 23 — Project 1: Calculator (Part 1)

## 🎯 Goal
Plan and start building a fully functional calculator app.

## 🧠 Project Overview
You'll build a text-based calculator that:
- Takes two numbers from the user
- Asks for an operation (+, -, *, /)
- Shows the result
- Loops so the user can keep calculating
- Handles errors (like dividing by zero)

## Step 1: Plan First (Don't Code Yet!)

In plain English, write out what the program does:
```
1. Show welcome message
2. Ask for first number
3. Ask for operation
4. Ask for second number
5. Calculate result based on operation
6. Handle divide-by-zero
7. Show result
8. Ask "Calculate again?" — if yes, loop back to step 2
9. If no, say goodbye
```

## Step 2: Build the Core Functions

```python
def add(a, b):
    return a + b

def subtract(a, b):
    return a - b

def multiply(a, b):
    return a * b

def divide(a, b):
    if b == 0:
        return "Error: Cannot divide by zero"
    return a / b

def calculate(a, op, b):
    if op == "+":
        return add(a, b)
    elif op == "-":
        return subtract(a, b)
    elif op == "*":
        return multiply(a, b)
    elif op == "/":
        return divide(a, b)
    else:
        return "Unknown operation"
```

Today: Build just these functions. Test them with hardcoded values.

## 👨‍💻 Coding Task
1. Write all 5 functions above
2. Test each manually:
```python
print(add(10, 5))        # 15
print(subtract(10, 5))   # 5
print(multiply(10, 5))   # 50
print(divide(10, 5))     # 2.0
print(divide(10, 0))     # Error message
print(calculate(7, "+", 3))  # 10
```

## 🔍 Prediction Task
`calculate(10, "/", 0)` — what will it return?

## 💥 Break-It Task
What happens if you pass a string instead of a number to `add()`?

## 🧩 Reflection
> Why build separate `add()`, `subtract()` etc. functions instead of putting all logic in `calculate()`?

*Estimated time: 45–60 min*
[Next: Day 24 →](./day-24.md)
