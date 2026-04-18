# 🧮 Project 1: Python Calculator

## Overview
A command-line calculator with full error handling.

**Concepts practiced:** Functions, loops, conditionals, user input, error handling, try/except

**Time to complete:** Day 23-25 (3 days)

**Difficulty:** Beginner

---

## Features
- Basic operations: +, -, *, /
- Input validation (handles letters, symbols)
- Division by zero protection
- Loop to keep calculating until user quits

## Step-by-Step Build Guide

### Step 1: Individual Operation Functions
Start by writing 4 separate functions:
```python
def add(a, b): ...
def subtract(a, b): ...
def multiply(a, b): ...
def divide(a, b): ...  # Handle zero division!
```
Test each one before moving on.

### Step 2: Safe Number Input
Write a function that gets a number and handles bad input:
```python
def get_number(prompt):
    while True:
        try:
            return float(input(prompt))
        except ValueError:
            print("Invalid number. Try again.")
```

### Step 3: Main Calculator Loop
Combine everything into a main function with a while loop:
- Ask for operation
- Ask for two numbers
- Show result
- Repeat until user types 'quit'

### Step 4: Polish
- Add a welcome banner
- Format results nicely
- Handle invalid operations

---

## Extension Challenges
1. Add square root: `import math`, then `math.sqrt(num)`
2. Add power: `num1 ** num2`
3. Keep a history list of all calculations
4. Add a "view history" option
5. Add a "clear history" option

---

## Completed Code
See Day 24 in /daily-grind/day-24.md for the full solution.

## What You'll Learn
- How to structure a real program
- Error handling with try/except
- The value of helper functions
- How to test edge cases
