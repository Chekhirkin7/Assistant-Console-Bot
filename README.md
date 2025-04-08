# 🤖 Assistant-Console-Bot

**Assistant-Console-Bot** is a console-based assistant bot for managing contacts. It works directly in the terminal, stores data across sessions, and supports managing phone numbers and birthdays.

---

## 🔍 Features

- ➕ Add contacts with one or multiple phone numbers
- 🔄 Edit phone numbers
- 🔍 Search phone numbers by contact name or find contact by phone number
- 🎂 Add and view birthdays
- 📅 Display upcoming birthdays (with weekend adjustments)
- 💾 Automatically saves data to `addressbook.pkl`

---

## 🛠️ Installation and Setup

```bash
git clone https://github.com/your-username/Assistant-Console-Bot.git
cd Assistant-Console-Bot
python main.py
```
⚠️ Python 3.7+ is required. No additional libraries are needed — everything is part of the standard Python library.

---

## 💡 Commands List

| Command                             | Description                                        |
|-------------------------------------|----------------------------------------------------|
| `hello`                             | Greet the assistant                               |
| `add John 0987654321`               | Add a contact with a name and phone number        |
| `change John 0987654321 0931234567` | Change an old phone number to a new one           |
| `phone John`                        | Show all phone numbers for the contact            |
| `all`                               | Display all saved contacts                        |
| `add-birthday John 15.04.1990`      | Add a birthday for a contact                      |
| `show-birthday John`                | Show the birthday for the contact                 |
| `birthdays`                         | Show upcoming birthdays in the next 7 days       |
| `close` or `exit`                   | Close the bot and save the data                   |


---

## 🗃️ Project Structure

```bash
Assistant-Console-Bot/
├── main.py             # Main bot logic and code
├── addressbook.pkl     # Contact storage file (auto-created)
└── README.md           # This file
```

---

## ✅ Requirements
Python 3.7 or newer

OS: Windows / macOS / Linux

Data is automatically saved in the addressbook.pkl file whenever changes are made.

