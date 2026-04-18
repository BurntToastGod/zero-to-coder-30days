# Day 21 — Functions + Lists Together

## 🎯 Goal
Write functions that work with lists.

## 🧠 Concept: Functions That Take Lists

```python
def get_average(numbers):
    total = 0
    for n in numbers:
        total += n
    return total / len(numbers)

scores = [85, 92, 78, 95, 88]
print(get_average(scores))   # 87.6

# Functions can also BUILD lists
def get_evens(numbers):
    evens = []
    for n in numbers:
        if n % 2 == 0:
            evens.append(n)
    return evens

print(get_evens([1,2,3,4,5,6,7,8]))  # [2, 4, 6, 8]
```

## 👨‍💻 Coding Task
Write these functions:
1. `find_max(numbers)` — returns the largest number in a list
2. `count_above(numbers, threshold)` — returns count of numbers above threshold
3. `reverse_list(items)` — returns a new list in reverse order
4. Test each with a list of 8 numbers

## 🔍 Prediction Task
```python
def sum_list(nums):
    total = 0
    for n in nums:
        total += n
    return total

print(sum_list([1, 2, 3, 4, 5]))    # Guess: ___
print(sum_list([10, 20]))            # Guess: ___
print(sum_list([]))                  # What happens? ___
```

## 💥 Break-It Task
Pass a string instead of a list to your function. What happens?

## 🧩 Reflection
> How do functions make working with lists easier?

*Estimated time: 45 min*
[Next: Day 22 →](./day-22.md)
