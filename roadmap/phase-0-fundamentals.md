# Phase 0 — Fundamentals
**Days 1–5 | Your First Steps in Code**

---

## 🎯 Learning Objective
By the end of Phase 0, you will be able to:
- Store information in variables
- Understand the 4 basic data types
- Print output to the screen
- Take input from the user
- Do basic math with code

---

## 🧠 What Is Programming, Really?

Programming is just **giving instructions to a computer** — in a language it understands.

Think of it like writing a recipe:
- You list steps in order
- Each step must be clear and exact
- The computer follows them literally (no guessing!)

Python is the language we use. It reads almost like English.

---

## 📌 Topic 1: Variables

A **variable** is a box that holds a piece of information.
You give it a name, then put something inside it.

```python
# This creates a variable called 'name' and stores "Alex" inside it
name = "Alex"
age = 25
height = 5.9

print(name)    # Output: Alex
print(age)     # Output: 25
```

### Why variables?
Without variables, you'd have to retype values everywhere.
With variables, you change one place and it updates everywhere.

### Rules for naming variables:
- No spaces (use underscores: `my_name` not `my name`)
- Start with a letter, not a number
- Case-sensitive: `Name` and `name` are different

---

## 📌 Topic 2: Data Types

Not all information is the same type. Python has 4 basics:

| Type | What it holds | Example |
|------|--------------|----------|
| `str` | Text (string) | `"Hello"` |
| `int` | Whole numbers | `42` |
| `float` | Decimal numbers | `3.14` |
| `bool` | True or False | `True` |

```python
greeting = "Hello, world!"   # str
score = 100                   # int
temperature = 98.6            # float
is_raining = False            # bool

print(type(greeting))   # <class 'str'>
print(type(score))      # <class 'int'>
```

---

## 📌 Topic 3: Print & Input

```python
# Print sends text to the screen
print("Hello!")
print("My name is", name)

# Input asks the user to type something
user_name = input("What is your name? ")
print("Nice to meet you,", user_name)
```

**Important:** `input()` always gives back a string, even if they type a number!

```python
number = input("Enter a number: ")  # number is a string!
real_number = int(number)            # Now it's an integer
```

---

## 📌 Topic 4: Basic Math

```python
x = 10
y = 3

print(x + y)   # 13  (addition)
print(x - y)   # 7   (subtraction)
print(x * y)   # 30  (multiplication)
print(x / y)   # 3.333... (division)
print(x // y)  # 3   (integer division - drops the decimal)
print(x % y)   # 1   (modulo - remainder)
print(x ** y)  # 1000 (power: 10 to the 3rd)
```

---

## 🔍 Prediction Tasks

Before running this code, write down what you THINK each line will print:

```python
a = 5
b = 2
print(a + b)     # Your guess: ___
print(a * b)     # Your guess: ___
print(a ** b)    # Your guess: ___
print(a % b)     # Your guess: ___
```

---

## 💪 Exercises

**Exercise 1:** Create 3 variables — your name, your age, and your favorite number. Print all three.

**Exercise 2:** Ask the user for two numbers. Add them together and print the result.

**Exercise 3:** Store your name in a variable. Print: `"Hello, [name]! Welcome to coding."`

**Exercise 4:** What happens if you try `"5" + 5`? Try it. Why does it error?

---

## 💥 Break-It Tasks

1. Try to create a variable named `2cool` — what error do you get?
2. Try `print("Hello" + 5)` — what happens? Why?
3. Delete the quotes around a string value — what error appears?

---

## 🧩 Reflection

Answer these in your head (or write them down):
1. What is a variable, in your own words?
2. Why does `input()` always return a string?
3. What's the difference between `/` and `//`?

---

## ⤵️ Next Phase
[Phase 1 — Logic & Conditionals](./phase-1-logic.md)
