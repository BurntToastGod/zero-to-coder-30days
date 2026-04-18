# 🕹️ Project 3: Text Adventure Game

## Overview
A text-based adventure game with multiple rooms, an inventory system, and story choices.

**Concepts practiced:** Nested dictionaries, lists, while loops, string methods, functions, game state

**Time to complete:** Day 27-28 (2 days)

**Difficulty:** Intermediate

---

## Features
- Multiple connected rooms
- Item pickup system
- Command parser (go, take, look, quit)
- Win/lose conditions
- Easily expandable map

## Step-by-Step Build Guide

### Step 1: Define Your Rooms
Create a dictionary with room names as keys:
```python
rooms = {
    "start": {
        "description": "...",
        "exits": {"north": "forest"},
        "items": ["torch"]
    },
    ...
}
```

### Step 2: The show_room Function
Print: description, available items, available exits, current inventory.

### Step 3: The Command Parser
Split user input: `command = input().strip().lower().split()`
Handle: go [direction], take [item], look, quit

### Step 4: Game Loop
While loop that:
1. Shows current room
2. Gets user command
3. Processes command
4. Updates game state
5. Checks win/lose conditions

### Step 5: Add Story
Make it interesting! Add a goal, obstacles, and rewards.

---

## Extension Challenges
1. Add an NPC (non-player character) to talk to
2. Add health points that decrease in dangerous areas
3. Create a locked door that requires a key
4. Add a final boss that requires a specific item to defeat
5. Add a save/load system using a simple dictionary

---

## Completed Code
See Day 27 in /daily-grind/day-27.md for the full solution.

## What You'll Learn
- Nested data structures (dicts inside dicts)
- How games manage state
- String parsing and command processing
- How to design expandable systems
