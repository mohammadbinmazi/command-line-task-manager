**Task Manager**

This is a simple Node.js command-line task manager application that allows users to manage tasks by adding, listing, and removing them. The tasks are stored in a JSON file (tasks.json) for persistence. created by mohammad bin mazi

**Features**

Add tasks to a list.

View all tasks in the list.

Remove tasks by their index number.

Prerequisites

To run this project, you need to have the following installed:

Node.js (v12 or later)
Project Structure

app.js: The main application file containing the logic for adding, listing, and removing tasks.

tasks.json: A JSON file used to store the tasks persistently.

**How It Works**

Add Tasks:

Reads the existing tasks from tasks.json.

Appends the new task to the list.

Saves the updated list back to tasks.json.

List Tasks:

Reads and displays all tasks from tasks.json.

Remove Tasks:

Reads the tasks from tasks.json.

Removes the specified task by index.

Saves the updated list back to tasks.json.

**Future Enhancements**

Add validation for commands and arguments.

Provide feedback for empty task lists or invalid operations.

Allow additional commands like editing a task or marking it as complete.

Support asynchronous file operations for better performance.

**License**

This project is open-source and available for personal or educational use. Contributions are welcome!
