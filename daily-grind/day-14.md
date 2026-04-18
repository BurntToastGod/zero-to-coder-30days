# Day 14 — Loops + Lists Together

## 🎯 Goal
Combine loops and lists to process collections of data.

## 🧠 Concept: Looping Through Lists

```python
scores = [85, 92, 78, 95, 88]

# Print each score
for score in scores:
    print(score)

# Find the total
total = 0
for score in scores:
    total += score
print("Total:", total)
print("Average:", total / len(scores))

# Find the highest
highest = scores[0]
for score in scores:
    if score > highest:
        highest = score
print("Highest:", highest)
```

## 👨‍💻 Coding Task
Create a list of 5 test scores. Write code that:
1. Prints all scores
2. Calculates and prints the average
3. Prints whether each score is passing (>= 60) or failing
4. Counts how many are passing

## 🔍 Prediction Task
```python
words = ["hello", "world", "python"]
for word in words:
    print(word.upper())
```
What will print? ___

## 💥 Break-It Task
Create an empty list `[]` and try to access index 0. What error?

## 🧩 Reflection
> How is looping through a list different from looping with `range()`?

*Estimated time: 45 min*
[Next: Day 15 →](./day-15.md)
