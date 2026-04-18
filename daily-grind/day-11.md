# Day 11 — for Loops & range()

## 🎯 Goal
Repeat code using for loops and understand range().

## 🧠 Concept

```python
# Print 0 to 4
for i in range(5):
    print(i)

# Print 1 to 5
for i in range(1, 6):
    print(i)

# Print 0, 2, 4, 6, 8
for i in range(0, 10, 2):
    print(i)
```

`range(start, stop, step)` — stop is NOT included.

The variable `i` is just a counter. You can use it:
```python
for i in range(1, 6):
    print(i, "x", 3, "=", i * 3)
```

## 👨‍💻 Coding Task
1. Print a countdown from 10 to 1 (then print "Go!")
2. Print the first 10 multiples of 7
3. Print a box of stars: 5 rows of 5 stars each

## 🔍 Prediction Task
```python
for i in range(3):
    print(i * i)  # Guess each line: ___

total = 0
for i in range(1, 5):
    total += i
print(total)  # Guess: ___
```

## 💥 Break-It Task
- What does `range(5, 0)` produce?
- What does `range(5, 0, -1)` produce?

## 🧩 Reflection
> What does `i` actually represent in the loop? Why is it named `i`?

*Estimated time: 30–45 min*
[Next: Day 12 →](./day-12.md)
