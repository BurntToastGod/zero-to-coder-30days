# Day 02 — Data Types

---

## 🎯 Goal of the Day
Learn the 4 basic data types and understand why they matter.

---

## 🧠 Concept: The 4 Data Types

Not all data is the same. Python has 4 basics:

| Type | What it holds | Example |
|------|--------------|----------|
| `str` | Text | `"Hello"` |
| `int` | Whole numbers | `42` |
| `float` | Decimal numbers | `3.14` |
| `bool` | True or False | `True` |

```python
name = "Jordan"      # str
score = 100          # int
temperature = 98.6   # float
is_sunny = True      # bool

print(type(name))        # <class 'str'>
print(type(score))       # <class 'int'>
print(type(temperature)) # <class 'float'>
print(type(is_sunny))    # <class 'bool'>
```

---

## 👨‍💻 Coding Task

Create one variable of EACH type (str, int, float, bool). Print each variable AND its type.

```python
# Example structure:
my_text = ???
my_number = ???
my_decimal = ???
my_bool = ???

print(my_text, type(my_text))
# ... do the same for the other 3
```

---

## 🔍 Prediction Task

```python
print(type(42))       # Guess: ___
print(type(42.0))     # Guess: ___
print(type("42"))     # Guess: ___
print(type(True))     # Guess: ___
```

---

## 💥 Break-It Task

Try converting between types:
```python
num_str = "100"
result = num_str + 50   # Will this work? Why or why not?
```

Now try fixing it with `int(num_str)` and see if it works.

---

## 🧩 Reflection
> Why does Python need different types? Why can't everything just be text?

---

*Estimated time: 30–45 minutes*
[Next: Day 03 →](./day-03.md)
