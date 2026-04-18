# Day 22 — Functions Review + Phase 3 Challenge

## 🎯 Goal
Build a complete mini-program using only functions.

## 🧠 Review: Functions Mastery Checklist
- [ ] Define a function with `def`
- [ ] Pass parameters into functions
- [ ] Return values with `return`
- [ ] Use default parameters
- [ ] Pass lists to functions
- [ ] Combine functions + loops

## 👨‍💻 Big Challenge: Grade Report Generator

Build a program with these functions:

```python
def get_grade(score):
    # Returns A, B, C, D, or F based on score
    pass

def calculate_average(scores):
    # Returns average of all scores
    pass

def print_report(name, scores):
    # Prints each score + grade
    # Prints the average
    # Prints "PASS" or "FAIL" (average >= 60)
    pass

# Use it:
student_name = "Alex"
student_scores = [85, 72, 91, 68, 79]
print_report(student_name, student_scores)
```

Expected output:
```
=== Grade Report for Alex ===
Score 1: 85 (B)
Score 2: 72 (C)
Score 3: 91 (A)
Score 4: 68 (D)
Score 5: 79 (C)
Average: 79.0
Result: PASS
```

## 🔍 Prediction Task
Before running: what will the average be? What will the result be?

## 💥 Break-It Task
Call `print_report()` with an empty list. What breaks? Fix it.

## 🧩 Reflection
> You just wrote a complete program using ONLY functions. How does breaking it into functions make the code easier to understand?

## 🏆 Milestone!
Phase 3 complete! Read [`/roadmap/phase-3-functions.md`](../roadmap/phase-3-functions.md)

*Estimated time: 60 min*
[Next: Day 23 →](./day-23.md)
