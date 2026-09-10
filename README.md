# Task Tracker Using Python

## Overview

Task Tracker is a simple command-line application developed using Python. It helps users manage their daily tasks by allowing them to add, view, complete, and delete tasks.

This project is designed as a beginner-level Python project to practice basic programming concepts such as lists, dictionaries, loops, conditional statements, functions, and user input.

## Features

- Add new tasks
- View all tasks
- Mark tasks as completed
- Delete tasks
- Display task status as Pending or Completed
- Simple command-line interface

## Technologies Used

- Python
- VS Code
- Command Prompt / Terminal

## Project Structure

```text
Task-Tracker-Python/
│
├── task_tracker.py
└── README.md
```

## How to Run

### 1. Install Python

Make sure Python is installed on your computer.

Check the Python version using:

```bash
python --version
```

### 2. Open the Project

Open the `Task-Tracker-Python` folder in VS Code.

### 3. Run the Program

Open the terminal in VS Code and run:

```bash
python task_tracker.py
```

## How the Program Works

When the program starts, it displays a menu with five options:

```text
===== TASK TRACKER =====
1. Add Task
2. View Tasks
3. Complete Task
4. Delete Task
5. Exit
```

The user can select an option by entering the corresponding number.

### Add Task

Select option `1` and enter the task.

Example:

```text
Enter your choice: 1
Enter task: Study Python
Task added successfully.
```

### View Tasks

Select option `2` to display all tasks.

Example:

```text
Your Tasks:
1. Study Python - Pending
2. Complete project - Pending
```

### Complete Task

Select option `3` and enter the task number.

Example:

```text
Enter task number to complete: 1
Task marked as completed.
```

The status will change to:

```text
1. Study Python - Completed
```

### Delete Task

Select option `4` and enter the task number.

Example:

```text
Enter task number to delete: 2
Deleted: Complete project
```

### Exit

Select option `5` to close the application.

```text
Thank you for using Task Tracker.
```

## Sample Output

```text
===== TASK TRACKER =====
1. Add Task
2. View Tasks
3. Complete Task
4. Delete Task
5. Exit

Enter your choice: 1
Enter task: Learn Python
Task added successfully.

===== TASK TRACKER =====
1. Add Task
2. View Tasks
3. Complete Task
4. Delete Task
5. Exit

Enter your choice: 2

Your Tasks:
1. Learn Python - Pending

Enter your choice: 3
Enter task number to complete: 1
Task marked as completed.

Enter your choice: 2

Your Tasks:
1. Learn Python - Completed
```

## Python Concepts Used

This project demonstrates the use of:

- Variables
- Lists
- Dictionaries
- `while` loops
- `if-elif-else` statements
- `for` loops
- `input()` function
- `append()` method
- `pop()` method
- `enumerate()` function
- Basic error and input validation

## Learning Outcomes

By completing this project, I learned how to:

- Create a basic Python command-line application
- Accept and process user input
- Store information using lists and dictionaries
- Use loops and conditional statements
- Update and delete data
- Build a simple menu-driven application
- Organize a beginner-level Python project for GitHub

## Future Improvements

The project can be improved by adding:

- Permanent task storage using a JSON or CSV file
- Task due dates
- Task priorities
- Search and filter options
- Better input validation
- Edit task functionality
- A graphical user interface
- Database integration

## Project Purpose

This project was developed as a practical Python project to strengthen programming fundamentals and gain hands-on experience in developing a simple real-world application.

## Author

**Yashaswini Yerramsetty**

B.Tech Electronics and Communication Engineering Student
