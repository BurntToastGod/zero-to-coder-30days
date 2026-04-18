# Day 03 — User Input & String Tricks

## 🎯 Goal
Get input from the user and manipulate strings.

## 🧠 Concept: input() and Strings

```python
name = input("What is your name? ")
print("Hello, " + name + "!")
print("Hello,", name + "!")
print(f"Hello, {name}!")  # f-string (easiest way!)
```

f-strings let you drop variables directly into text using `{}`.

```python
age = 25
print(f"You are {age} years old.")
print(f"In 10 years you will be {age + 10}.")
```

## 👨‍💻 Coding Task
Ask the user for their name and city. Print:
`"Welcome, [name]! Great to hear you're from [city]."`

Use an f-string.

## 🔍 Prediction Task
```python
first = "Hello"
second = "World"
print(first + " " + second)  # Guess: ___
print(len(first))             # Guess: ___
print(first.upper())          # Guess: ___
```

## 💥 Break-It Task
Try adding a number to a string directly:
```python
age = input("Your age: ")
print(age + 5)  # Does this work?
```
Fix it. Why did it break?

## 🧩 Reflection
> Why does `input()` always return a string, even if you type a number?

*Estimated time: 30–45 min*
[Next: Day 04 →](./day-04.md)
