# 🔄 Loops Practice

Use after: Day 11-15

## Exercise 1: Countdown (Beginner)
Write a loop that counts DOWN from 10 to 1, then prints "Blast off!"

---

## Exercise 2: Sum Calculator (Beginner)
Ask the user for 5 numbers one at a time.
Use a loop to collect them.
Print the total and average.

---

## Exercise 3: Multiplication Table (Intermediate)
Ask for a number.
Print its multiplication table from 1 to 12.

Example (for 7):
```
7 x 1 = 7
7 x 2 = 14
...
7 x 12 = 84
```

---

## Exercise 4: Password Validator (Intermediate)
Keep asking for a password until the user enters one that:
- Is at least 8 characters long
- Contains at least one number

Print "Password accepted!" when valid.
Print what's wrong when invalid.

**Hint:** Use `any(char.isdigit() for char in password)` to check for numbers.

---

## Exercise 5: Number Pattern (Hard)
Write code that prints this pattern for n=5:
```
1
1 2
1 2 3
1 2 3 4
1 2 3 4 5
```

Ask the user for `n`. No hints.

---

## Exercise 6: FizzBuzz (Hard)
Classic interview question:
- For numbers 1-100
- If divisible by 3: print "Fizz"
- If divisible by 5: print "Buzz"
- If divisible by both: print "FizzBuzz"
- Otherwise: print the number

Do it in as few lines as possible.
