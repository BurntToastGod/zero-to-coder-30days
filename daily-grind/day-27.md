# Day 27 - 🕹️ Build a Text Adventure Game

## 🎯 Goal
Build a simple text-based adventure game — your third project!

## 🧠 Concept: Nested Dictionaries & Game State
Games need to track state — where you are, what you have, what's happened.

```python
# Game state dictionary
game = {
    "player": {
        "name": "",
        "health": 100,
        "inventory": []
    },
    "current_room": "start",
    "visited": []
}
```

## 🕹️ The Adventure Game

```python
rooms = {
    "start": {
        "description": "You are in a dark cave. There is a TORCH on the ground.",
        "exits": {"north": "forest", "east": "river"},
        "items": ["torch"]
    },
    "forest": {
        "description": "You are in a dense forest. You hear wolves nearby.",
        "exits": {"south": "start", "east": "castle"},
        "items": []
    },
    "river": {
        "description": "You are by a river. There is a SWORD here.",
        "exits": {"west": "start", "north": "castle"},
        "items": ["sword"]
    },
    "castle": {
        "description": "You reach the castle. You WIN!",
        "exits": {},
        "items": []
    }
}

def show_room(room_name, inventory):
    room = rooms[room_name]
    print(f"\n{room['description']}")
    if room["items"]:
        print(f"Items here: {', '.join(room['items'])}")
    print(f"Exits: {', '.join(room['exits'].keys())}")
    print(f"Inventory: {inventory if inventory else 'empty'}")

def play_game():
    current_room = "start"
    inventory = []

    print("=== Text Adventure ===")
    print("Commands: go [direction], take [item], quit")

    while current_room != "castle":
        show_room(current_room, inventory)
        command = input("\nWhat do you do? ").strip().lower().split()

        if not command:
            continue

        action = command[0]

        if action == "quit":
            print("Thanks for playing!")
            break
        elif action == "go" and len(command) > 1:
            direction = command[1]
            if direction in rooms[current_room]["exits"]:
                current_room = rooms[current_room]["exits"][direction]
            else:
                print("You can't go that way!")
        elif action == "take" and len(command) > 1:
            item = command[1]
            if item in rooms[current_room]["items"]:
                inventory.append(item)
                rooms[current_room]["items"].remove(item)
                print(f"You picked up the {item}!")
            else:
                print(f"There is no {item} here.")
        else:
            print("I don't understand that command.")

    if current_room == "castle":
        show_room(current_room, inventory)

play_game()
```

## 🧑‍💻 Your Task
1. Type and run the adventure game
2. Add a new room called "dungeon"
3. Add a "dragon" enemy that requires the sword to defeat

## 🌙 Extension Challenges
- Add HP (health points) that decrease in dangerous rooms
- Add a "look" command that re-describes the room
- Create a map with 8+ rooms

## 🔍 Prediction Task
What happens if you type "go" without a direction?

## 🧩 Reflection
> Games are just programs with state. What other things in real life are just 'state + rules'?
