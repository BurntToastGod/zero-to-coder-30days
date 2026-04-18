# Day 19 — Default Parameters & Multiple Returns

## 🎯 Goal
Make functions more flexible with default values.

## 🧠 Concept: Default Parameters

```python
# greeting has a default value
def greet(name, greeting="Hello"):
    return f"{greeting}, {name}!"

print(greet("Alice"))              # Hello, Alice!
print(greet("Bob", "Good day"))    # Good day, Bob!
print(greet("Carol", "Hey"))       # Hey, Carol!
```

Default parameters must come AFTER non-default ones:
```python
# WRONG: def greet(greeting="Hello", name) — Error!
# RIGHT: def greet(name, greeting="Hello")
```

## Multiple Return Values

```python
def min_max(numbers):
    return min(numbers), max(numbers)

lowest, highest = min_max([3, 1, 4, 1, 5, 9, 2, 6])
print(lowest)    # 1
print(highest)   # 9
```

## 👨‍💻 Coding Task
1. Write `power(base, exp=2)` — returns base raised to exp (default: squared)
2. Write `describe_number(n)` — returns two values: whether it's even/odd AND positive/negative
3. Write `greet_user(name, language="english")` that greets in English ("Hello") or Spanish ("Hola")

## 🔍 Prediction Task
```python
def describe(item, qty=1, unit="item"):
    return f"{qty} {unit}(s) of {item}"

print(describe("apple"))             # Guess: ___
print(describe("orange", 3))         # Guess: ___
print(describe("milk", 2, "carton")) # Guess: ___
```

## 💥 Break-It Task
Try putting a default parameter before a required one.

## 🧩 Reflection
> When are default parameters useful? Give a real example.

*Estimated time: 30–45 min*
[Next: Day 20 →](./day-20.md)
