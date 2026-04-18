# Day 07 — if / else

## 🎯 Goal
Write code that makes decisions using if and else.

## 🧠 Concept: if / else

```python
age = 18

if age >= 18:
    print("You can vote!")
else:
    print("Too young to vote.")
```

The colon `:` is REQUIRED. The indentation (4 spaces) is REQUIRED.
Python knows what's "inside" the if block by the indentation.

```python
temperature = 35

if temperature > 30:
    print("It's hot outside!")
    print("Wear sunscreen.")
else:
    print("Comfortable weather.")
```

## 👨‍💻 Coding Task
Ask the user for their age. Print one of these messages:
- Under 13: "You're a child."
- 13 to 17: "You're a teenager."
- 18 or older: "You're an adult."

Use if/else.

## 🔍 Prediction Task
```python
x = 15
if x > 10:
    print("big")
else:
    print("small")
```
What will print? ___

```python
if 5 > 10:
    print("A")
else:
    print("B")
```
What will print? ___

## 💥 Break-It Task
1. Remove the `:` after `if age >= 18` — what error?
2. Remove the indentation on the `print` inside the if block — what error?
3. What happens if you put `else:` without an `if` before it?

## 🧩 Reflection
> When does the `else` block run? When does it NOT run?

*Estimated time: 30–45 min*
[Next: Day 08 →](./day-08.md)
