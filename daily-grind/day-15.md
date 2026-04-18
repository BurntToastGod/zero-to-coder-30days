# Day 15 — break, continue & Loop Patterns

## 🎯 Goal
Control loops precisely with break and continue.

## 🧠 Concept

```python
# break: exit the loop immediately
for i in range(10):
    if i == 5:
        break
    print(i)    # Prints 0,1,2,3,4

# continue: skip the rest of this iteration
for i in range(10):
    if i % 2 == 0:
        continue
    print(i)    # Prints 1,3,5,7,9
```

## Common Loop Patterns

```python
# Pattern: Search a list
names = ["Alice", "Bob", "Charlie", "Diana"]
found = False
for name in names:
    if name == "Charlie":
        found = True
        break
print("Found:", found)

# Pattern: Collect matching items
evens = []
for i in range(20):
    if i % 2 == 0:
        evens.append(i)
print(evens)
```

## 👨‍💻 Coding Task
1. Loop through numbers 1-20. Print only those divisible by 3.
2. Search a list of names for one specific name. Print "Found" or "Not found".
3. Collect all numbers from 1-50 that are divisible by both 3 AND 5.

## 🔍 Prediction Task
```python
for i in range(1, 8):
    if i == 4:
        continue
    if i == 6:
        break
    print(i)
```
List all output values: ___

## 💥 Break-It Task
What happens if you use `break` outside of any loop?

## 🧩 Reflection
> What's the difference between `break` and `continue` in one sentence?

*Estimated time: 45 min*
[Next: Day 16 →](./day-16.md)
