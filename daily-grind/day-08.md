# Day 08 — elif (Multiple Conditions)

## 🎯 Goal
Handle multiple conditions using elif.

## 🧠 Concept: elif

`elif` means "else if" — check another condition if the first one was False.

```python
score = 75

if score >= 90:
    print("Grade: A")
elif score >= 80:
    print("Grade: B")
elif score >= 70:
    print("Grade: C")
elif score >= 60:
    print("Grade: D")
else:
    print("Grade: F")
```

Python checks from top to bottom. The FIRST match wins. It stops there.

## 👨‍💻 Coding Task
Build a temperature descriptor:
- Above 35: "Scorching hot"
- 25 to 35: "Hot"
- 15 to 25: "Comfortable"
- 5 to 15: "Cool"
- Below 5: "Cold"

Ask the user for a temperature and print the descriptor.

## 🔍 Prediction Task
```python
x = 75
if x >= 90:
    print("A")
elif x >= 80:
    print("B")
elif x >= 70:
    print("C")
else:
    print("F")
```
What prints? ___

Now change x to 95. What prints? ___
Change x to 50. What prints? ___

## 💥 Break-It Task
What happens if you write `elif` without an `if` before it?

## 🧩 Reflection
> If the score is 85, will the `elif score >= 70` branch ever run? Why not?

*Estimated time: 30 min*
[Next: Day 09 →](./day-09.md)
