# Day 12 — while Loops

## 🎯 Goal
Use while loops to repeat code until a condition is false.

## 🧠 Concept

```python
# while loops keep running WHILE condition is True
count = 0
while count < 5:
    print(count)
    count += 1   # count = count + 1
# Output: 0 1 2 3 4
```

Use `while` when you don't know how many times to loop:

```python
answer = ""
while answer != "quit":
    answer = input("Type something (or 'quit' to stop): ")
    print("You typed:", answer)
print("Goodbye!")
```

## 👨‍💻 Coding Task
Build a number guessing game:
- Pick a secret number (just hard-code it: `secret = 42`)
- Ask the user to guess
- If too high: print "Too high!"
- If too low: print "Too low!"
- Keep asking until they get it right
- When correct: print "You got it in X guesses!"

## 🔍 Prediction Task
```python
x = 10
while x > 0:
    print(x)
    x -= 3
```
List all the output values: ___

## 💥 Break-It Task
Remove the `count += 1` line from the first example. Run it. What happens? (Press Ctrl+C to stop)

## 🧩 Reflection
> When would you choose `while` over `for`? Give a real example.

*Estimated time: 45 min*
[Next: Day 13 →](./day-13.md)
