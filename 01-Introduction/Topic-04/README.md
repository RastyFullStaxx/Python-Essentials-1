# 🚀 Topic 4: Your First Real Python Program — A Smart Greeter

---

## 🧭 Overview

You've already printed `"Hello, World!"`, so now it's time to level up.

This lesson walks you through creating your **first interactive Python program**. Instead of just displaying a fixed message, you’ll write a smart greeter that:
- Accepts user input
- Processes it
- Returns a personalized message

Let’s start building meaningful interactions with code!

---

## 🎯 Learning Objectives

By the end of this lesson, you’ll be able to:

- Use the `input()` function to accept user input
- Store data in variables
- Use string concatenation and f-strings to personalize output
- Understand how Python executes instructions line-by-line
- Optionally: Wrap your code in a reusable function

---

## 👨‍💻 Step-by-Step: Build the Smart Greeter

### 📝 Step 1: Accept User Input

```python
name = input("What's your name? ")
```

This line asks the user to type something. Whatever they type will be stored in the variable `name`.

---

### 📝 Step 2: Display a Personalized Greeting

```python
print("Hello, " + name + "! Welcome to Python.")
```

Or, using **f-strings** (cleaner and preferred):

```python
print(f"Hello, {name}! Welcome to Python.")
```

---

### 🧪 Try it Together

```python
# smart_greeter.py

name = input("What's your name? ")
print(f"Hello, {name}! Welcome to Python.")
```

▶ Save the file and run it. When prompted, enter your name.

🖥 Output:
```
What's your name? Hugo
Hello, Hugo! Welcome to Python.
```

---

## 🌟 Optional: Wrap It in a Function

```python
def greet_user():
    name = input("What's your name? ")
    print(f"Hello, {name}! Welcome to Python.")

greet_user()
```

Using a function makes it easier to reuse and extend your program later.

---

## 🛠 Bonus Challenge (Optional)

Try modifying your program to ask the user:

- Their **favorite color**
- Their **hobby**
- Then print a friendly response using that info

```python
name = input("Your name: ")
color = input("Favorite color: ")
hobby = input("Your hobby: ")

print(f"Hey {name}, it's awesome that you like {color} and enjoy {hobby}!")
```

---

## ✅ Key Concepts Recap

| Concept     | Description                                       |
|-------------|---------------------------------------------------|
| `input()`   | Accepts user input from the terminal              |
| Variables   | Store values like text or numbers                 |
| `print()`   | Displays output to the screen                     |
| f-strings   | Easy, readable way to embed variables in strings  |
| Functions   | Organize and reuse blocks of code                 |

---

## 🔜 Coming Up Next

Now that you’ve written your first **interactive program**, we’ll move on to understanding **data types and variables** in more depth.

---

## 🙌 Tip of the Day

> “The best programs don’t just speak—they listen.”

---
