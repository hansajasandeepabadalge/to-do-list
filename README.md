### Description

This Python script is a simple command-line To-Do List application. It allows users to manage their tasks through a text-based interface. The application provides the following functionalities:

1. **Add Task**: Users can add multiple tasks to their to-do list.
2. **Show Tasks**: Users can view all the tasks along with their completion status (Done/Not Done).
3. **Mark Task as Done**: Users can mark a specific task as completed.
4. **Exit**: Users can exit the application.

### Usage

1. **Run the Script**: Execute the script using Python.
   ```sh
   python todolist.py
   ```

2. **Menu Options**:
   - **Add Task**: Select option [`1`](command:_github.copilot.openSymbolFromReferences?%5B%221%22%2C%5B%7B%22uri%22%3A%7B%22%24mid%22%3A1%2C%22fsPath%22%3A%22d%3A%5C%5CCodeX%5C%5CTo%20Do%20List%5C%5Ctodolist.py%22%2C%22_sep%22%3A1%2C%22external%22%3A%22file%3A%2F%2F%2Fd%253A%2FCodeX%2FTo%2520Do%2520List%2Ftodolist.py%22%2C%22path%22%3A%22%2FD%3A%2FCodeX%2FTo%20Do%20List%2Ftodolist.py%22%2C%22scheme%22%3A%22file%22%7D%2C%22pos%22%3A%7B%22line%22%3A5%2C%22character%22%3A15%7D%7D%5D%5D "Go to definition") and enter the number of tasks you want to add. Then, input each task.
   - **Show Tasks**: Select option [`2`](command:_github.copilot.openSymbolFromReferences?%5B%222%22%2C%5B%7B%22uri%22%3A%7B%22%24mid%22%3A1%2C%22fsPath%22%3A%22d%3A%5C%5CCodeX%5C%5CTo%20Do%20List%5C%5Ctodolist.py%22%2C%22_sep%22%3A1%2C%22external%22%3A%22file%3A%2F%2F%2Fd%253A%2FCodeX%2FTo%2520Do%2520List%2Ftodolist.py%22%2C%22path%22%3A%22%2FD%3A%2FCodeX%2FTo%20Do%20List%2Ftodolist.py%22%2C%22scheme%22%3A%22file%22%7D%2C%22pos%22%3A%7B%22line%22%3A6%2C%22character%22%3A15%7D%7D%5D%5D "Go to definition") to display all tasks with their status.
   - **Mark Task as Done**: Select option [`3`](command:_github.copilot.openSymbolFromReferences?%5B%223%22%2C%5B%7B%22uri%22%3A%7B%22%24mid%22%3A1%2C%22fsPath%22%3A%22d%3A%5C%5CCodeX%5C%5CTo%20Do%20List%5C%5Ctodolist.py%22%2C%22_sep%22%3A1%2C%22external%22%3A%22file%3A%2F%2F%2Fd%253A%2FCodeX%2FTo%2520Do%2520List%2Ftodolist.py%22%2C%22path%22%3A%22%2FD%3A%2FCodeX%2FTo%20Do%20List%2Ftodolist.py%22%2C%22scheme%22%3A%22file%22%7D%2C%22pos%22%3A%7B%22line%22%3A7%2C%22character%22%3A15%7D%7D%5D%5D "Go to definition") and enter the task number to mark it as done.
   - **Exit**: Select option [`4`](command:_github.copilot.openSymbolFromReferences?%5B%224%22%2C%5B%7B%22uri%22%3A%7B%22%24mid%22%3A1%2C%22fsPath%22%3A%22d%3A%5C%5CCodeX%5C%5CTo%20Do%20List%5C%5Ctodolist.py%22%2C%22_sep%22%3A1%2C%22external%22%3A%22file%3A%2F%2F%2Fd%253A%2FCodeX%2FTo%2520Do%2520List%2Ftodolist.py%22%2C%22path%22%3A%22%2FD%3A%2FCodeX%2FTo%20Do%20List%2Ftodolist.py%22%2C%22scheme%22%3A%22file%22%7D%2C%22pos%22%3A%7B%22line%22%3A8%2C%22character%22%3A15%7D%7D%5D%5D "Go to definition") to exit the application.

### Example

```sh
====== TO-DO List ======
1. Add Task
2. Show Tasks
3. Mark Task as Done
4. Exit
Enter your choice: 1

How many task you want to add: 2
Enter the task: Buy groceries
Task Added!
Enter the task: Call mom
Task Added!

====== TO-DO List ======
1. Add Task
2. Show Tasks
3. Mark Task as Done
4. Exit
Enter your choice: 2

Tasks:
1. Buy groceries - Not Done
2. Call mom - Not Done

====== TO-DO List ======
1. Add Task
2. Show Tasks
3. Mark Task as Done
4. Exit
Enter your choice: 3

Enter the task number to mark as done: 1
Task marked as done!

====== TO-DO List ======
1. Add Task
2. Show Tasks
3. Mark Task as Done
4. Exit
Enter your choice: 2

Tasks:
1. Buy groceries - Done
2. Call mom - Not Done
```

### Requirements

- Python 3.x
