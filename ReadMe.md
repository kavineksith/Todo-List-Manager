## Documentation : Todo List Manager 

## Overview

The Todo List Manager is a command-line application designed to manage a list of tasks using SQLite for persistent storage. This Python script provides a robust interface for users to add, update, delete, mark as completed, and search tasks. It utilizes SQLite for database management and includes essential error handling to ensure smooth operation.

## Features

- **Create and Manage Tasks**: Easily create new tasks, update existing ones, and delete tasks.
- **Mark Tasks as Completed**: Track the completion status of tasks with a simple update.
- **Search Functionality**: Search for tasks containing specific keywords using partial matches.
- **View All Tasks**: Display a complete list of all tasks along with their completion status.
- **Error Handling**: Gracefully handles user input errors, file operations, and unexpected interruptions.

## Dependencies

- **Python 3.x**: The script is compatible with Python 3.x.
- **SQLite**: Utilizes SQLite for database operations. No additional libraries are required beyond Python's built-in `sqlite3` module.
- **Standard Libraries**: Includes Python’s built-in libraries:
  - `sqlite3` for database management.
  - `sys` for system-specific parameters and functions.
  - `re` for regular expressions (although not explicitly used, it may be useful for advanced searches).

## Usage

To use the Todo List Manager, follow these steps:

1. **Obtain the Script**: Download or clone the Python script file.
2. **Run the Script**: Execute the script using Python from your command line or terminal:

   ```bash
   python todo_app.py
   ```

3. **Interact with the Application**: Follow the on-screen prompts to manage your tasks.

## Interactive Commands

The Todo List Manager provides the following interactive commands:

1. **View All Tasks**:
   - **Command**: `1`
   - **Description**: Displays all tasks in the system with their IDs, descriptions, and completion status.
   - **Output**: List of all tasks.

2. **Add Task**:
   - **Command**: `2`
   - **Description**: Allows the user to add a new task.
   - **Prompt**: Enter the task description.

3. **Update Task**:
   - **Command**: `3`
   - **Description**: Updates the description of an existing task based on its ID.
   - **Prompts**: Enter the task ID, enter the new task description.

4. **Delete Task**:
   - **Command**: `4`
   - **Description**: Deletes a task from the list by specifying its ID.
   - **Prompt**: Enter the task ID to delete.

5. **Mark Task as Completed**:
   - **Command**: `5`
   - **Description**: Marks a task as completed based on its ID.
   - **Prompt**: Enter the task ID to mark as completed.

6. **Search Tasks**:
   - **Command**: `6`
   - **Description**: Searches for tasks containing a specific keyword. The search is performed using partial matches.
   - **Prompt**: Enter a keyword to search for in tasks.

7. **Exit**:
   - **Command**: `7`
   - **Description**: Exits the application.
   - **Output**: Exiting message.

## Special Commands

- **Error Handling**: The application includes error handling for invalid input (e.g., non-integer values where integers are expected) and unexpected interruptions (e.g., KeyboardInterrupt). It also manages database connection issues gracefully.
- **Keyboard Interrupt**: The script handles keyboard interruptions (Ctrl+C) to allow users to exit the application cleanly.

## Conclusion

The Todo List Manager is a versatile and user-friendly application for managing tasks through a command-line interface. With its robust features for task management, including creation, updates, deletion, and searching, it provides an effective tool for personal organization. The use of SQLite ensures persistent storage of tasks, while comprehensive error handling enhances the reliability and usability of the application.

For further customization or enhancement, users can modify the script to add additional features or integrate it with other tools as needed.

## **License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

### **Disclaimer:**
Kindly note that this project is developed solely for educational purposes, not intended for industrial use, as its sole intention lies within the realm of education. We emphatically underscore that this endeavor is not sanctioned for industrial application. It is imperative to bear in mind that any utilization of this project for commercial endeavors falls outside the intended scope and responsibility of its creators. Thus, we explicitly disclaim any liability or accountability for such usage.
