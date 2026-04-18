# Day 06 — Comparisons & True/False

## 🎯 Goal
Understand comparison operators and boolean values.

## 🧠 Concept: Comparisons Return True or False

```python
print(5 > 3)    # True
print(5 < 3)    # False
print(5 == 5)   # True  (== checks equality, NOT assignment!)
print(5 != 4)   # True  (not equal)
print(5 >= 5)   # True
print(5 <= 4)   # False
```

Key insight: These comparisons produce `True` or `False`.
You can store them in variables too:
```python
is_adult = age >= 18
print(is_adult)  # True or False depending on age
```

## 👨‍💻 Coding Task
Ask the user for a number. Print:
- Is it greater than 100? (True/False)
- Is it equal to 42? (True/False)
- Is it negative? (True/False)

## 🔍 Prediction Task
```python
x = 7
print(x > 5)       # Guess: ___
print(x == 7)      # Guess: ___
print(x != 7)      # Guess: ___
print(x >= 10)     # Guess: ___
```

## 💥 Break-It Task
Try `x = 5 == 5` then print x. What do you think x contains?

## 🧩 Reflection
> What's the difference between `=` and `==`? Why does this matter?

*Estimated time: 30 min*
[Next: Day 07 →](./day-07.md)
