# Day 04 — Math & Numbers

## 🎯 Goal
Master Python's math operators and understand integer vs float division.

## 🧠 Concept: All the Math Operators

```python
# Basic math
print(10 + 3)   # 13 addition
print(10 - 3)   # 7  subtraction
print(10 * 3)   # 30 multiplication
print(10 / 3)   # 3.333... division (always gives float)
print(10 // 3)  # 3  integer division (drops decimal)
print(10 % 3)   # 1  modulo (remainder)
print(10 ** 3)  # 1000 exponent (10 to the power of 3)
```

The `%` (modulo) is super useful for checking if numbers are even or odd:
```python
if 8 % 2 == 0:
    print("even")
```

## 👨‍💻 Coding Task
Ask the user for two numbers. Print ALL of the following:
- Sum, difference, product, quotient
- Integer quotient and remainder
- First number to the power of the second

## 🔍 Prediction Task
```python
print(17 % 5)     # Guess: ___
print(17 // 5)    # Guess: ___
print(2 ** 8)     # Guess: ___
print(9 % 3)      # Guess: ___
```

## 💥 Break-It Task
```python
print(5 / 0)   # What happens?
```
How would you handle this error so the program doesn't crash?

## 🧩 Reflection
> What is the modulo operator useful for in real programs?

*Estimated time: 30 min*
[Next: Day 05 →](./day-05.md)
