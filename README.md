# To-Do List Application

## Overview

This project implements a simple **To-Do List** application using Python. The `ToDoList` class allows users to:

- Add tasks
- Edit existing tasks
- Delete tasks by their ID
- Print all tasks in the to-do list

## Features

1. **Add Task**: Users can add tasks with a unique task ID and a name.
2. **Edit Task**: Modify the name of an existing task by providing its ID.
3. **Delete Task**: Remove tasks from the list by their ID.
4. **Print Tasks**: View all tasks that are currently in the list.

## How It Works

The class `ToDoList` has the following methods:

- `add_task(task_id, task_name)`: Adds a task if the task ID does not already exist.
- `edit_task(task_id, new_task_name)`: Edits the name of a task with the given ID.
- `delete_task(task_id)`: Deletes the task with the provided ID.
- `print_tasks()`: Prints out all the tasks in the list, showing their IDs and names.

### Example Usage

Here’s an example of how to use the `ToDoList` class:

```python
# Creating an instance of ToDoList
todo = ToDoList()

# Adding tasks
todo.add_task(1, "Hey I am first task")
todo.add_task(2, "This is the second task")

# Editing a task
todo.edit_task(1, "Updated first task")

# Deleting a task
todo.delete_task(2)

# Printing all tasks
todo.print_tasks()
```

### Expected Output:

```
Task 'Hey I am first task' added successfully.
Task 'This is the second task' added successfully.
Task with id 1 updated to 'Updated first task'.
Task with id 2 deleted.
To-Do List:
Task ID: 1, Task Name: Updated first task
```

## Installation and Setup

1. **Requirements**: 
    - Python 3.x
  
2. **Steps**:
    - Download the script or clone the repository.
    - Ensure Python is installed on your system.

3. **Running the Application**:
    - Open your terminal or command prompt.
    - Navigate to the directory where the script is saved.
    - Run the script using the command: 
      ```
      python todo_list.py
      ```
