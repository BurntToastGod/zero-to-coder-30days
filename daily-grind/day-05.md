# Day 05 — Putting It Together (Phase 0 Review)

## 🎯 Goal
Combine everything from Days 1-4 into a single mini-program.

## 🧠 Concept Review: Everything So Far
- Variables store data
- 4 types: str, int, float, bool
- `input()` gets user input (always returns str)
- Math operators: +, -, *, /, //, %, **
- `print()` and f-strings

## 👨‍💻 Coding Task: Personal Info Calculator

Build a program that:
1. Asks for the user's name
2. Asks for their birth year
3. Calculates their approximate age (2026 - birth year)
4. Asks for their height in feet
5. Converts it to inches (multiply by 12)
6. Prints a summary using f-strings:

```
Name: Alex
Age: ~26 years old
Height: 5.9 feet = 70.8 inches
```

## 🔍 Prediction Task
```python
year = int(input("Birth year: "))
current_year = 2026
age = current_year - year
print(f"You are approximately {age} years old.")
```
If you type 2000, what will it print? ___

## 💥 Break-It Task
Remove the `int()` conversion from `int(input(...))`. What error do you get when you try to calculate `current_year - year`?

## 🧩 Reflection
> Look back at Day 01. What can you do now that you couldn't do 5 days ago?

## 🏆 Milestone!
You finished Phase 0 — Fundamentals. Read [`/roadmap/phase-0-fundamentals.md`](../roadmap/phase-0-fundamentals.md) to review.

*Estimated time: 45–60 min*
[Next: Day 06 →](./day-06.md)
