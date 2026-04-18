# Phase 3 — Functions
**Days 17–22 | Writing Reusable Code Blocks**

---

## 🎯 Learning Objective
By the end of Phase 3, you will be able to:
- Define and call your own functions
- Use parameters to pass information into functions
- Use `return` to get values back out
- Understand variable scope (local vs global)
- Write clean, reusable code

---

## 🧠 What Is a Function?

A function is a **named block of code** that you can run whenever you want.

Think of it like a recipe with a name:
- You write the recipe once
- You "call" it (use it) as many times as you want
- You can change the ingredients (parameters) each time

---

## 📌 Topic 1: Defining and Calling Functions

```python
# Define a function (write the recipe)
def say_hello():
    print("Hello, world!")

# Call a function (use the recipe)
say_hello()   # Output: Hello, world!
say_hello()   # Output: Hello, world!
say_hello()   # Output: Hello, world!
```

Notice: `def` means "define". The function name is followed by `()`.
Nothing runs until you CALL the function.

---

## 📌 Topic 2: Parameters (Inputs to Functions)

```python
def greet(name):
    print("Hello,", name)

greet("Alex")    # Output: Hello, Alex
greet("Sam")     # Output: Hello, Sam
greet("Jordan")  # Output: Hello, Jordan

# Multiple parameters
def add(a, b):
    print(a + b)

add(3, 4)   # Output: 7
add(10, 20) # Output: 30
```

---

## 📌 Topic 3: Return Values

So far, functions just print things. But functions can also **give back** a value.

```python
def add(a, b):
    return a + b

result = add(3, 4)
print(result)   # Output: 7

# You can use the returned value directly
print(add(10, 20) * 2)   # Output: 60
```

**The difference:**
- `print()` shows something on screen — for humans to see
- `return` sends a value back to the code that called the function — for code to use

---

## 📌 Topic 4: Default Parameters

```python
def greet(name, greeting="Hello"):
    print(greeting + ", " + name)

greet("Alex")              # Hello, Alex
greet("Alex", "Good day")  # Good day, Alex
```

---

## 📌 Topic 5: Scope (Local vs Global)

```python
name = "Global"   # global variable

def show_name():
    name = "Local"   # local variable (only exists inside this function)
    print(name)      # prints "Local"

show_name()
print(name)  # still prints "Global" - the function didn't change it!
```

Variables created inside a function are LOCAL — they only exist inside that function.

---

## 🔍 Prediction Tasks

```python
def double(n):
    return n * 2

print(double(5))           # Guess: ___
print(double(double(3)))   # Guess: ___

def mystery(x, y):
    return x * y + 1

print(mystery(3, 4))  # Guess: ___
```

---

## 💪 Exercises

**Exercise 1:** Write a function `square(n)` that returns n squared.

**Exercise 2:** Write a function `is_even(n)` that returns `True` if n is even, `False` if odd.

**Exercise 3:** Write a function `max_of_two(a, b)` that returns the larger of two numbers.

**Exercise 4:** Write a function `celsius_to_fahrenheit(c)` that converts temperature. Formula: `(c * 9/5) + 32`

---

## 💥 Break-It Tasks

1. Call a function BEFORE defining it — what error do you get?
2. Try to access a local variable from outside the function
3. Forget the `return` keyword — what does the function return by default?

---

## 🧩 Reflection
1. Why use functions instead of just writing the code directly?
2. What's the difference between `print` inside a function vs `return`?
3. What happens to a local variable when the function finishes?

---

## ⤵️ Next Phase
[Phase 4 — Projects](./phase-4-projects.md)
