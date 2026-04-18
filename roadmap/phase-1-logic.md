# Phase 1 — Logic & Conditionals
**Days 6–10 | Teaching Your Code to Make Decisions**

---

## 🎯 Learning Objective
By the end of Phase 1, you will be able to:
- Compare values with comparison operators
- Use `if`, `elif`, and `else` to branch your code
- Combine conditions with `and`, `or`, `not`
- Understand boolean logic

---

## 🧠 What Is Logic in Code?

Right now your code runs line-by-line, top to bottom, no matter what.
Logic lets your code **make decisions** — like a fork in the road.

> If it's raining, bring an umbrella. Otherwise, don't.

That's exactly what `if/else` does in Python.

---

## 📌 Topic 1: Comparison Operators

These return `True` or `False`:

```python
print(5 > 3)    # True
print(5 < 3)    # False
print(5 == 5)   # True  (== means "is equal to")
print(5 != 3)   # True  (! means "not")
print(5 >= 5)   # True
print(5 <= 4)   # False
```

**Common mistake:** `=` assigns a value. `==` compares two values.
`age = 25` means "set age to 25"
`age == 25` means "is age equal to 25?"

---

## 📌 Topic 2: if / elif / else

```python
age = 18

if age >= 18:
    print("You can vote!")
else:
    print("Too young to vote.")
```

The colon `:` starts the block. The indentation (4 spaces) is REQUIRED.

```python
score = 75

if score >= 90:
    print("A")
elif score >= 80:
    print("B")
elif score >= 70:
    print("C")
else:
    print("F")
```

Python checks from top to bottom and stops at the FIRST match.

---

## 📌 Topic 3: Boolean Logic (and / or / not)

```python
age = 20
has_id = True

# Both must be True
if age >= 18 and has_id:
    print("Welcome!")

# At least one must be True
if age >= 21 or has_id:
    print("Entry allowed")

# Flip True to False, False to True
if not has_id:
    print("Need ID")
```

---

## 🔍 Prediction Tasks

```python
x = 10
y = 5

if x > y:
    print("bigger")       # Will this print? ___
if x == 10 and y == 5:
    print("both match")   # Will this print? ___
if x < 5 or y < 10:
    print("at least one") # Will this print? ___
```

---

## 💪 Exercises

**Exercise 1:** Ask the user for their age. Print if they are a child (<13), teen (13-17), or adult (18+).

**Exercise 2:** Ask for a number. Print if it's positive, negative, or zero.

**Exercise 3:** Ask for two numbers. Print which one is larger (or if they're equal).

**Exercise 4:** Build a simple password checker — if the user types the right password, print "Access granted", else print "Wrong password".

---

## 💥 Break-It Tasks

1. Remove the `:` from an `if` statement — what error appears?
2. Remove the indentation from inside an `if` block — what happens?
3. Try using `=` instead of `==` in a condition

---

## 🧩 Reflection
1. What's the difference between `=` and `==`?
2. If you have `if/elif/elif/else`, can more than one branch run? Why not?
3. What does `and` require vs what does `or` require?

---

## ⤵️ Next Phase
[Phase 2 — Loops](./phase-2-loops.md)
