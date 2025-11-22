# Personal Task Manager (Console-Based)

A simple, lightweight **command-line task management system** written in Python. This program allows users to create an account, store personal information, add tasks with targets, and track task progress — all saved locally in plain text files.

Perfect for learning file handling in Python or for anyone who wants a minimal, no-dependency personal task tracker.

## Features

- User registration and login (with plain text password storage)
- Secure per-user data storage (`username_data.txt`)
- Add multiple tasks with descriptions and targets
- Update and view task progress (Completed / Ongoing / Not Started)
- Separate task status log with timestamps
- Simple text-based menu interface

## Warning: Security Note

> **This project stores passwords in plain text** and is intended **for educational purposes only**.  
> Do **not** use this in production or with sensitive information.

## Requirements

- Python 3.x (No external libraries required)

## How to Run

1. Save the script as `task_manager.py`
2. Open terminal/command prompt
3. Run the program:

```bash
python task_manager.py
