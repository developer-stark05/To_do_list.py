# 📝 To-Do List Project

A simple and interactive command-line based To-Do List application built in Python.  
This project helps users manage tasks efficiently by adding, marking, deleting, swapping, and reviewing tasks—all through a friendly terminal interface.

---

## 💡 Features

- ✅ Add tasks to your to-do list  
- ✔️ Mark tasks as completed  
- 🔄 Swap tasks to reorder priorities  
- 🗑️ Delete tasks from the list  
- 🧹 Clear all tasks from either list  
- 📋 Review both pending and completed tasks

---

## 🛡️ Error Handling

This project includes robust error handling to ensure smooth user experience:

- 🧠 **Input Validation**: Prevents empty or whitespace-only tasks from being added.
- 🔢 **Index Checks**: Ensures task numbers entered for marking, deleting, or swapping are within valid range.
- 🔁 **Duplicate Prevention**: Avoids marking the same task as completed more than once.
- ❌ **Graceful Exits**: Recognizes `'Enough()'` as a safe keyword to exit loops without crashing.
- 🗣️ **Friendly Prompts**: Guides users with clear messages when incorrect inputs are detected.

These checks make the app beginner-friendly and emotionally intelligent—just like its creator 💖

---

## 🛠️ How It Works

- The app runs in a loop, allowing users to choose operations interactively.
- Input validation ensures smooth user experience.
- Tasks are stored in two lists:
  - `do_list`: for pending tasks
  - `done_list`: for completed tasks

---

## 📦 Requirements

- Python 3.x  
- No external libraries required

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/todo-list-python.git
