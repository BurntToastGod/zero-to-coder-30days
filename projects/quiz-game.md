# 🎮 Project 2: Quiz Game

## Overview
A text-based quiz game with score tracking and multiple question types.

**Concepts practiced:** Lists, dictionaries, loops, conditionals, functions, f-strings

**Time to complete:** Day 26-27 (2 days)

**Difficulty:** Beginner-Intermediate

---

## Features
- Multiple choice and free-text questions
- Score tracking with percentage
- Pass/fail rating system
- Easy to add new questions

## Step-by-Step Build Guide

### Step 1: Question Data
Store questions as a list of dictionaries:
```python
questions = [
    {"question": "...", "answer": "...", "hint": "..."},
    ...
]
```

### Step 2: Question Loop
Loop through each question, get user input, check answer.

### Step 3: Score Tracking
Increment score when correct. Calculate percentage at end.

### Step 4: Feedback System
Show different messages based on score percentage.

### Step 5: Add Your Own Questions
Personalize the quiz with topics YOU care about.

---

## Extension Challenges
1. Add multiple-choice options (A, B, C, D)
2. Shuffle questions with `random.shuffle()`
3. Add a high score tracker across multiple games
4. Create a "categories" system
5. Allow players to create their own questions

---

## Completed Code
See Day 26 in /daily-grind/day-26.md for the full solution.

## What You'll Learn
- How to use lists of dictionaries
- How to loop with index using enumerate()
- How to use .lower() for case-insensitive comparisons
- How to calculate and display percentages
