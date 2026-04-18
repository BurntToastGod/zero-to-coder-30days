# Day 10 — Logic Review + Mini Challenge

## 🎯 Goal
Apply everything from Phase 1 (Logic) in a real challenge.

## 🧠 Review: Everything in Phase 1
- Comparison operators: `>`, `<`, `==`, `!=`, `>=`, `<=`
- `if` / `elif` / `else` for decisions
- `and` / `or` / `not` for combining conditions

## 👨‍💻 Coding Challenge: Smart Calculator

Build a program that:
1. Asks for two numbers
2. Asks for an operation (+, -, *, /)
3. If division, checks if second number is 0 (can't divide by zero!)
4. Shows the result

```python
# Structure hint:
num1 = float(input("First number: "))
op = input("Operation (+, -, *, /): ")
num2 = float(input("Second number: "))

if op == "+":
    print(num1 + num2)
elif op == "-":
    print(num1 - num2)
elif op == "*":
    print(num1 * num2)
elif op == "/":
    if num2 == 0:
        print("Error: Cannot divide by zero!")
    else:
        print(num1 / num2)
else:
    print("Unknown operation")
```

## 🔍 Prediction Task
If user enters: 10, /, 0 — what will print?
If user enters: 5, +, 3 — what will print?

## 💥 Break-It Task
Remove the zero-check and try dividing by 0. What error do you get?

## 🧩 Reflection
> Look at the calculator. It handles many different cases. How is this different from code that just does one thing?

## 🏆 Milestone!
Phase 1 complete! Read [`/roadmap/phase-1-logic.md`](../roadmap/phase-1-logic.md)

*Estimated time: 45–60 min*
[Next: Day 11 →](./day-11.md)
