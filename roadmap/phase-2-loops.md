# Phase 2 — Loops
**Days 11–16 | Doing Things Over and Over**

---

## 🎯 Learning Objective
By the end of Phase 2, you will be able to:
- Use `for` loops to repeat code a set number of times
- Use `while` loops to repeat until a condition is met
- Use `range()` to generate sequences
- Use `break` and `continue` to control loops
- Recognize and fix infinite loops

---

## 🧠 What Is a Loop?

A loop is a way to run the same code multiple times WITHOUT writing it over and over.

Without loops:
```python
print("Hello")
print("Hello")
print("Hello")
print("Hello")
print("Hello")
```

With a loop:
```python
for i in range(5):
    print("Hello")
```
Same result. Way less code.

---

## 📌 Topic 1: for Loops

```python
# Basic for loop
for i in range(5):
    print(i)     # Prints 0, 1, 2, 3, 4

# range(start, stop)
for i in range(1, 6):
    print(i)     # Prints 1, 2, 3, 4, 5

# range(start, stop, step)
for i in range(0, 10, 2):
    print(i)     # Prints 0, 2, 4, 6, 8
```

`range(5)` means: start at 0, go up to (but NOT including) 5.

---

## 📌 Topic 2: Looping Over Lists

```python
fruits = ["apple", "banana", "cherry"]

for fruit in fruits:
    print(fruit)
# Output:
# apple
# banana
# cherry
```

---

## 📌 Topic 3: while Loops

```python
count = 0
while count < 5:
    print(count)
    count = count + 1   # IMPORTANT: must update count or loops forever!
```

Use `while` when you don't know in advance how many times to loop.

```python
password = ""
while password != "secret123":
    password = input("Enter password: ")
print("Access granted!")
```

---

## 📌 Topic 4: break and continue

```python
# break stops the loop entirely
for i in range(10):
    if i == 5:
        break
    print(i)   # Prints 0, 1, 2, 3, 4

# continue skips the rest of THIS iteration
for i in range(10):
    if i % 2 == 0:
        continue
    print(i)   # Prints only odd numbers: 1, 3, 5, 7, 9
```

---

## ⚠️ The Infinite Loop Trap

```python
# DANGER: This loops forever!
count = 0
while count < 5:
    print(count)
    # FORGOT to update count!
```

Always make sure your `while` loop's condition will eventually become False.
If you're stuck in one, press `Ctrl+C` to stop it.

---

## 🔍 Prediction Tasks

```python
for i in range(3):
    print(i * 2)     # Guess each output: ___

total = 0
for i in range(1, 5):
    total = total + i
print(total)          # Guess the final total: ___
```

---

## 💪 Exercises

**Exercise 1:** Print a countdown from 10 to 1, then print "Blast off!"

**Exercise 2:** Print the multiplication table for 7 (7x1 through 7x10).

**Exercise 3:** Ask the user to keep guessing a number until they guess 42. Tell them "too high" or "too low" each time.

**Exercise 4:** Sum all numbers from 1 to 100 using a loop. (Answer should be 5050.)

---

## 💥 Break-It Tasks

1. Create a `while True:` loop with no `break` — what happens? (Use Ctrl+C to stop)
2. Change `range(5)` to `range(5, 0)` — what happens? Why?
3. Remove the increment from a while loop counter — observe the infinite loop

---

## 🧩 Reflection
1. When would you use `for` vs `while`?
2. What does `range(2, 10, 3)` produce?
3. What's the difference between `break` and `continue`?

---

## ⤵️ Next Phase
[Phase 3 — Functions](./phase-3-functions.md)
