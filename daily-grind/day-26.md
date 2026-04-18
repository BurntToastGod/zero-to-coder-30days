# Day 26 - 🎮 Build a Quiz Game

## 🎯 Goal
Build a text-based quiz game from scratch — your second real project!

## 🧠 Concept: Dictionaries
Dictionaries store data as key-value pairs:

```python
# Dictionary syntax
person = {
    "name": "Alice",
    "age": 25,
    "city": "Phoenix"
}

# Access values
print(person["name"])   # Alice
print(person["age"])    # 25

# Add new key
person["job"] = "developer"

# Loop through dictionary
for key, value in person.items():
    print(f"{key}: {value}")
```

## 🎮 The Quiz Game

```python
questions = [
    {
        "question": "What is 2 + 2?",
        "answer": "4",
        "hint": "It's not 5"
    },
    {
        "question": "What color is the sky?",
        "answer": "blue",
        "hint": "Look up on a sunny day"
    },
    {
        "question": "How many days in a week?",
        "answer": "7",
        "hint": "Monday through Sunday"
    }
]

def run_quiz(questions):
    score = 0
    total = len(questions)

    print("=== Python Quiz Game ===")
    print(f"You have {total} questions. Good luck!")
    print()

    for i, q in enumerate(questions):
        print(f"Question {i + 1}: {q['question']}")
        answer = input("Your answer: ").strip().lower()

        if answer == q["answer"].lower():
            print("Correct!")
            score += 1
        else:
            print(f"Wrong! The answer was: {q['answer']}")
        print()

    print(f"Quiz complete! Score: {score}/{total}")
    percentage = (score / total) * 100
    print(f"You got {percentage:.0f}%")

    if percentage >= 80:
        print("Excellent work!")
    elif percentage >= 50:
        print("Good effort!")
    else:
        print("Keep practicing!")

run_quiz(questions)
```

## 🧑‍💻 Your Task
1. Type the quiz game and run it
2. Add 3 more questions of your own
3. Add a hint system: if the user types "hint", show the hint and let them try again

## 🌙 Extension Challenges
- Shuffle the questions randomly (use `import random` and `random.shuffle()`)
- Add a timer for each question
- Save the high score between sessions

## 🔍 Prediction Task
What does `enumerate(questions)` do? Why is it useful here?

## 🧩 Reflection
> You built a quiz! What other types of games could use this same structure?
