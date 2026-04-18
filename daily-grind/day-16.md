# Day 16 — Loops Review + Loop Challenge

## 🎯 Goal
Review all loop concepts and tackle a larger challenge.

## 🧠 Review: All Loop Concepts
- `for i in range(n)` — repeat n times
- `for item in list` — loop through a list
- `while condition` — repeat until condition is False
- `break` — exit loop immediately
- `continue` — skip to next iteration

## 👨‍💻 Big Challenge: FizzBuzz

FizzBuzz is a classic programming challenge:
- Print numbers 1 to 100
- If divisible by 3: print "Fizz" instead
- If divisible by 5: print "Buzz" instead
- If divisible by BOTH 3 and 5: print "FizzBuzz"

```python
# Hint:
for i in range(1, 101):
    if i % 3 == 0 and i % 5 == 0:
        print("FizzBuzz")
    elif i % 3 == 0:
        print("Fizz")
    elif i % 5 == 0:
        print("Buzz")
    else:
        print(i)
```

Try to write this WITHOUT looking at the hint first!

## 🔍 Prediction Task
What does this print for numbers 15, 30, 7, 9?

## 💥 Break-It Task
Swap the order — check `% 3 == 0` and `% 5 == 0` separately BEFORE checking the combined. What goes wrong? Why?

## 🧩 Reflection
> FizzBuzz tests if/elif/else AND loops together. What concept was hardest to apply?

## 🏆 Milestone!
Phase 2 complete! Read [`/roadmap/phase-2-loops.md`](../roadmap/phase-2-loops.md)

*Estimated time: 45–60 min*
[Next: Day 17 →](./day-17.md)
