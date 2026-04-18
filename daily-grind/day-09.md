# Day 09 — Boolean Logic (and / or / not)

## 🎯 Goal
Combine multiple conditions using and, or, not.

## 🧠 Concept

```python
age = 20
has_id = True

# AND: both must be True
if age >= 18 and has_id == True:
    print("Entry allowed")

# OR: at least one must be True
if age >= 65 or age < 12:
    print("Discounted ticket")

# NOT: flips True to False and vice versa
if not has_id:
    print("Please show ID")
```

Truth table:
- `True and True` = True
- `True and False` = False
- `False or True` = True
- `not True` = False

## 👨‍💻 Coding Task
Build a "can you ride this roller coaster?" checker:
- Must be at least 48 inches tall AND at least 12 years old
- Ask the user for both values
- Print whether they can ride or why not

## 🔍 Prediction Task
```python
a = True
b = False
print(a and b)   # Guess: ___
print(a or b)    # Guess: ___
print(not a)     # Guess: ___
print(not b)     # Guess: ___
```

## 💥 Break-It Task
What does `True and True and False and True` evaluate to? Why?

## 🧩 Reflection
> What's the key difference between `and` and `or`?

*Estimated time: 30 min*
[Next: Day 10 →](./day-10.md)
