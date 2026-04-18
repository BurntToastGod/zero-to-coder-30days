# Day 17 — Intro to Functions

## 🎯 Goal
Define and call your first functions.

## 🧠 Concept: What Is a Function?

A function is a named block of code you can run any time.
Write it once, use it many times.

```python
# DEFINE the function
def say_hello():
    print("Hello, world!")

# CALL the function (run it)
say_hello()   # Hello, world!
say_hello()   # Hello, world!
say_hello()   # Hello, world!
```

Without the call, NOTHING runs.
`def` just defines it. You must call it to run it.

## Functions with Parameters

```python
def greet(name):
    print(f"Hello, {name}!")

greet("Alice")   # Hello, Alice!
greet("Bob")     # Hello, Bob!
```

Parameters let you pass information INTO the function.

## 👨‍💻 Coding Task
1. Write a function `say_hi()` that prints "Hi there!"
2. Write a function `greet(name)` that says hello to any name
3. Write a function `shout(text)` that prints text in ALL CAPS
4. Call each function at least 3 times with different values

## 🔍 Prediction Task
```python
def double(x):
    print(x * 2)

double(5)    # Guess: ___
double(0)    # Guess: ___
double(-3)   # Guess: ___
```

## 💥 Break-It Task
Call a function BEFORE defining it. What error appears?

## 🧩 Reflection
> Why would you wrap code in a function instead of just writing it directly?

*Estimated time: 30–45 min*
[Next: Day 18 →](./day-18.md)
