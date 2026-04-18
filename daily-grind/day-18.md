# Day 18 — Return Values

## 🎯 Goal
Understand the difference between printing and returning from a function.

## 🧠 Concept: return

```python
# This function PRINTS (humans see it)
def add_print(a, b):
    print(a + b)

# This function RETURNS (code can use the result)
def add_return(a, b):
    return a + b
```

The BIG difference:
```python
result = add_print(3, 4)   # Prints 7, but result = None
result = add_return(3, 4)  # Silent, but result = 7

print(result)   # 7
print(add_return(5, 6) * 2)  # 22 (you can use the return value in expressions!)
```

Functions that `return` values are like machines:
- You put something IN (parameters)
- You get something OUT (return value)

## 👨‍💻 Coding Task
1. Write `square(n)` — returns n squared
2. Write `cube(n)` — returns n cubed
3. Write `celsius_to_f(c)` — returns `(c * 9/5) + 32`
4. Write `is_even(n)` — returns True if n is even, False if odd
5. Test each by storing the return value and printing it

## 🔍 Prediction Task
```python
def multiply(a, b):
    return a * b

print(multiply(3, 4))          # Guess: ___
print(multiply(2, multiply(3, 4)))  # Guess: ___
x = multiply(5, 6)
print(x + 1)                   # Guess: ___
```

## 💥 Break-It Task
```python
def add(a, b):
    return a + b
    print("Done")  # What happens to this line?
```

## 🧩 Reflection
> When would you want to `return` instead of `print` in a function?

*Estimated time: 30–45 min*
[Next: Day 19 →](./day-19.md)
