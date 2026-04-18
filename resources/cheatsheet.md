# 📝 Python Cheatsheet

Quick reference for everything you've learned.

---

## Variables & Types
```python
name = "Alice"          # string
age = 25                # integer
price = 9.99            # float
is_active = True        # boolean

# Type conversion
int("42")       # string -> int
float("3.14")   # string -> float
str(42)         # int -> string
type(variable)  # check the type
```

## User Input
```python
name = input("Enter name: ")      # always returns string
age = int(input("Enter age: "))   # convert to int
```

## String Methods
```python
text = "Hello World"
text.lower()           # "hello world"
text.upper()           # "HELLO WORLD"
text.strip()           # removes whitespace
text.split()           # ["Hello", "World"]
len(text)              # 11
f"My name is {name}"  # f-string formatting
```

## Math
```python
10 + 3   # 13
10 - 3   # 7
10 * 3   # 30
10 / 3   # 3.333...
10 // 3  # 3 (floor division)
10 % 3   # 1 (remainder)
10 ** 3  # 1000 (power)
```

## Conditionals
```python
if x > 10:
    print("big")
elif x > 5:
    print("medium")
else:
    print("small")

# Comparison operators
# ==  !=  >  <  >=  <=

# Boolean operators
# and  or  not
```

## Loops
```python
# For loop
for i in range(5):      # 0, 1, 2, 3, 4
    print(i)

for item in my_list:
    print(item)

for i, item in enumerate(my_list):
    print(i, item)

# While loop
while condition:
    # do something
    if done:
        break
    if skip:
        continue
```

## Lists
```python
my_list = [1, 2, 3, 4, 5]
my_list[0]           # first item
my_list[-1]          # last item
my_list.append(6)    # add to end
my_list.remove(3)    # remove value 3
my_list.pop()        # remove last item
len(my_list)         # number of items
3 in my_list         # True
```

## Dictionaries
```python
person = {"name": "Alice", "age": 25}
person["name"]         # "Alice"
person["job"] = "dev"  # add key
person.keys()           # all keys
person.values()         # all values
person.items()          # key-value pairs
```

## Functions
```python
def greet(name, greeting="Hello"):  # default param
    return f"{greeting}, {name}!"

result = greet("Alice")
result2 = greet("Bob", "Hi")
```

## Error Handling
```python
try:
    result = 10 / number
except ZeroDivisionError:
    print("Can't divide by zero")
except ValueError:
    print("Bad value")
except Exception as e:
    print(f"Error: {e}")
```

## Import & Random
```python
import random
random.randint(1, 10)     # random int between 1-10
random.choice(my_list)    # random item from list
random.shuffle(my_list)   # shuffle in place
```
