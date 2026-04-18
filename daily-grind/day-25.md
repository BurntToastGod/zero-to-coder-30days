# Day 25 - 🔧 Debugging Your Calculator

## 🎯 Goal
Learn to find and fix bugs systematically.

## 🧠 Concept: Debugging Like a Pro
Debugging is a skill, not luck. You need a process:
1. Read the error message carefully
2. Find the line number
3. Understand what the code expected vs what it got
4. Fix ONE thing at a time
5. Test after each fix

## 🐛 Common Python Errors

```python
# SyntaxError - you wrote something Python can't understand
if x = 5:  # WRONG - use == not =
    print(x)

# NameError - variable doesn't exist yet
print(result)  # WRONG if result was never defined

# TypeError - wrong type of data
age = input("Age: ")
new_age = age + 1  # WRONG - age is a string, not int
new_age = int(age) + 1  # RIGHT

# ZeroDivisionError
result = 10 / 0  # WRONG

# IndexError - list position doesn't exist
my_list = [1, 2, 3]
print(my_list[5])  # WRONG - only indexes 0, 1, 2 exist
```

## 🧑‍💻 Debug Challenge
These programs have bugs. Find and fix each one:

**Bug 1:**
```python
name = input("Name: ")
print("Hello " + Name)
```

**Bug 2:**
```python
numbers = [10, 20, 30]
total = 0
for i in range(4):
    total = total + numbers[i]
print(total)
```

**Bug 3:**
```python
def greet(person)
    print("Hello " + person)
greet("Alice")
```

## 🔍 Prediction Task
Before fixing Bug 2: what exact error will you see?

## 💥 Break-It Task
Take your calculator from Day 24 and deliberately introduce a bug. Then fix it!

## 🧩 Reflection
> What's the most confusing error message you've seen? What did you learn from it?
