# 🐛 Debugging Challenges

Use after: Day 25

Each program below has one or more bugs. Find them and fix them!

---

## Challenge 1: Name Bug
```python
first_name = input("First name: ")
last_name = input("Last name: ")
full_name = first_Name + " " + last_name
print("Hello, " + full_name)
```
**Bugs to find:** 1

---

## Challenge 2: Loop Bug
```python
total = 0
numbers = [1, 2, 3, 4, 5]
for i in range(6):
    total = total + numbers[i]
print("Total:", total)
```
**Bugs to find:** 1

---

## Challenge 3: Function Bug
```python
def calculate_area(width, height)
    area = width * height
    print(area)

result = calculate_area(5, 10)
print("Area is:", result)
```
**Bugs to find:** 2

---

## Challenge 4: Type Bug
```python
age = input("How old are you? ")
age_next_year = age + 1
print("Next year you'll be", age_next_year)
```
**Bugs to find:** 1

---

## Challenge 5: Logic Bug
```python
def is_adult(age):
    if age > 18:
        return True
    else:
        return False

print(is_adult(18))  # Should print True, not False!
```
**Bugs to find:** 1 (logic error, not syntax)

---

## Challenge 6: Hard Mode
This program is supposed to find the average of user-entered numbers.
Find ALL the bugs:

```python
def get_average(nums):
    total = 0
    for num in nums:
        total = total + num
    average = total / nums
    return averege

numbers = []
for i in range(5):
    n = input("Enter number: ")
    numbers.append(n)

result = get_average(numbers)
print(f"Average: {result}")
```
**Bugs to find:** 3
