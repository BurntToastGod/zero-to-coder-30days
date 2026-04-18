# Day 13 — Lists

## 🎯 Goal
Store multiple values in a list and loop through them.

## 🧠 Concept: Lists

A list holds multiple items in one variable:

```python
fruits = ["apple", "banana", "cherry"]
numbers = [10, 20, 30, 40, 50]
mixed = ["hello", 42, True, 3.14]

print(fruits[0])     # apple  (index starts at 0!)
print(fruits[1])     # banana
print(fruits[-1])    # cherry (last item)
print(len(fruits))   # 3 (number of items)
```

## Looping Over Lists

```python
for fruit in fruits:
    print(fruit)

# With index:
for i in range(len(fruits)):
    print(i, fruits[i])
```

## Modifying Lists

```python
fruits.append("mango")      # add to end
fruits.remove("banana")     # remove by value
fruits[0] = "avocado"       # change item by index
print(len(fruits))           # new length
```

## 👨‍💻 Coding Task
1. Create a list of 5 favorite foods
2. Print each one with a number (1. pizza, 2. tacos...)
3. Add a new food to the end
4. Print the total count

## 🔍 Prediction Task
```python
items = [10, 20, 30, 40]
print(items[2])          # Guess: ___
print(items[-1])         # Guess: ___
print(len(items))        # Guess: ___
items.append(50)
print(len(items))        # Guess: ___
```

## 💥 Break-It Task
Try `items[10]` on a list with only 4 items. What error appears?

## 🧩 Reflection
> Why is `items[0]` the FIRST item? Why not `items[1]`?

*Estimated time: 45 min*
[Next: Day 14 →](./day-14.md)
