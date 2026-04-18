# Day 20 — Scope & Functions in Loops

## 🎯 Goal
Understand variable scope and use functions inside loops.

## 🧠 Concept: Scope

```python
global_var = "I'm global"

def my_function():
    local_var = "I'm local"   # ONLY exists inside this function
    print(global_var)         # Can access global from inside function
    print(local_var)

my_function()
print(global_var)   # Works
# print(local_var)  # ERROR: local_var doesn't exist here
```

## Functions Inside Loops

```python
def is_even(n):
    return n % 2 == 0

numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
for num in numbers:
    if is_even(num):
        print(f"{num} is even")
```

This is the RIGHT way to structure code — small reusable functions + loops.

## 👨‍💻 Coding Task
1. Write `classify_score(score)` that returns "A", "B", "C", "D", or "F"
2. Create a list of 6 scores
3. Loop through the list and print each score's grade using your function

## 🔍 Prediction Task
```python
def add_one(n):
    return n + 1

result = 0
for i in range(5):
    result = add_one(result)
print(result)   # Guess: ___
```

## 💥 Break-It Task
Inside a function, try to modify a global variable directly. What happens?

## 🧩 Reflection
> Why is it better to put logic in a function than to repeat it inside every loop?

*Estimated time: 45 min*
[Next: Day 21 →](./day-21.md)
