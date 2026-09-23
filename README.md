# Task Tracker Using Python

## Project URL

https://roadmap.sh/projects/task-tracker

## Overview

Task Tracker is a simple command-line application developed using Python. It helps users manage daily tasks by allowing them to add, view, complete, and delete tasks.

This beginner-level project demonstrates practical Python programming concepts including lists, dictionaries, loops, conditional statements, user input, and exception handling.

## Features

- Add new tasks
- View all tasks
- Mark tasks as completed
- Delete tasks
- Display task status as Pending or Completed
- Handle invalid menu choices
- Validate task numbers
- Handle non-numeric task-number input without crashing
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

Make sure Python is installed.

Check the version:

```bash
python --version
```

### 2. Open the Project

Open the project folder in VS Code or Command Prompt.

### 3. Run the Program

From the project folder, run:

```bash
python task_tracker.py
```

## How the Program Works

When the program starts, it displays:

```text
===== TASK TRACKER =====
1. Add Task
2. View Tasks
3. Complete Task
4. Delete Task
5. Exit
```

The user selects an option by entering the corresponding number.

### Add Task

Select option `1`.

Example:

```text
Enter your choice: 1
Enter task: Study Python
Task added successfully.
```

### View Tasks

Select option `2`.

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

The status changes to:

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

### Input Validation

The application handles invalid task-number input.

For example, if the user enters:

```text
Enter task number to complete: abc
```

the program displays:

```text
Please enter a valid number.
```

The program continues running instead of terminating with a Python error.

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
- `try-except` exception handling
- Basic input validation

## Learning Outcomes

By completing this project, I learned how to:

- Create a Python command-line application
- Accept and process user input
- Store information using lists and dictionaries
- Use loops and conditional statements
- Update and delete data
- Handle invalid user input
- Build a simple menu-driven application
- Organize a beginner-level project for GitHub

## Future Improvements

Possible future improvements include:

- Permanent task storage using JSON or CSV
- Task due dates
- Task priorities
- Search and filter options
- Edit task functionality
- Graphical user interface
- Database integration

## Project Purpose

This project was developed as a practical Python project to strengthen programming fundamentals and gain hands-on experience in developing a simple real-world application.

## Author

Koushik
