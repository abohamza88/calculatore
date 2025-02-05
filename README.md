# Welcome
# 🌍 Welcome Chatbot - Personal Introduction Program

This is a simple Python script that interacts with the user, collects basic personal details, and provides a friendly conversation experience.

## 📌 Features
- Greets the user with a welcome message.
- Asks for the user's **name**, **age**, **job**, and **location**.
- Engages in a conversation by asking about their work satisfaction.
- Ends with a friendly farewell message.

## 📝 Code
```python
# General Welcome
print("    Welcome to our private world\n    ")
print("I love Python\nPython is very easy\n")

# Personal Introduction
name = input("What is your name?\n")
print("Hello, my friend " + name)
print("Nice to meet you!")

# Collecting personal details
age = input("What is your age?\n")
help = input("How can I help you?\n")
work = input("What is your work?\n")
print("Good job, " + work)

live = input("Where do you live?\n")
print("Beautiful country!")

about_your_live = input("Are you happy in your work?\n")
print("I wish you success!")

# Ending conversation
print("Goodbye, " + name)
wait = input("Wait a minute, I have a question for you, " + name + "?\n")
print("You are welcome, please!")

