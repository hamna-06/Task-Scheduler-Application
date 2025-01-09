# Task-Scheduler-Application
This is a task scheduling application using DSA principles such as AVL tree, priority queue (heap), Json files.<br>
The Task Scheduler Application is a Tkinter-based desktop tool designed to help users manage tasks efficiently.<br>
It allows users to add, update, delete, and search for tasks while providing an intuitive interface to visualize tasks in a tabular format.<br>
Each task includes attributes like name, deadline, and priority, with automatic calculation of days remaining until the deadline.<br>
This application is suitable for personal task tracking and offers a reliable, user-friendly way to stay organized.

<h2><b>Features:</b></h2>

<h4>Welcome Page:</h4>
1. Displays a welcome image using the PIL library.<br>
2. Includes a "Start" button to transition to the main application.<br>

<h4>Task Management:</h4>
<b>1. Add Task:</b> Adds a task with a name, deadline, and priority.<br>
<b>2. Update Task:</b> Updates the details (deadline, priority) of an existing task.<br>
<b>3. Delete Task:</b> Removes a task by name.<br>
<b>4. Search Task:</b> Finds a task by name and displays its details.<br>
<b>5. Sort Tasks:</b> Sorts tasks based on priority using a priority queue.<br>
<b>6. Clear Input:</b> Clears all input fields for convenience.<br>

<h4>Task Validation:</h4>
1. Task name must be at least 3 characters long, and it cannot contain special characters.<br>
2. Deadline must not be in the past.<br>
3. Priority must be a valid integer.<br>

<h4>Task Visualization:</h4>
Uses a Treeview widget to display tasks in a tabular format, showing:<br>
1. Task Name<br>
2. Deadline<br>
3. Priority<br>
4. Days Remaining<br>
5. Data Persistence:<br>
Tasks are saved in a JSON file (tasks.json) for persistence across sessions.<br>
Tasks are loaded from the file on application start.<br>
<h4>Automatic Deadline Calculation:</h4>
The Task class calculates the number of days left until the deadline.
<h4>Responsive Design:</h4>
Tasks and buttons are displayed dynamically using tk.Canvas, allowing for better positioning and resizing.








