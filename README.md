Project: Todo App with HTML, CSS and JS

Overview
Create a simple Todo App that allows users to add new tasks, edit existing tasks, mark tasks as completed, and delete completed tasks. The functionality should be implemented using JavaScript to manipulate the DOM. The provided HTML template already includes the basic structure and styling links.

Requirements


HTML Template Link: Find it in your resource section, named as "Todo App Project Template".

Task Addition:
When the user enters a task and clicks the "Add Task" button, the task should be added to the list of incomplete tasks.
If the input field is empty, no action should be taken.

Task Editing:
Allow users to edit an existing task. When the "Edit" button is clicked, the task text should appear in the input field.
Change the "Add Task" button to "Update Task" during editing.
Update the task text upon resubmission and then reset the button text back to "Add Task".

Marking Task as Completed:
When a task’s checkbox is checked, the task should be marked as completed.
Remove the checkbox and the "Edit" button from the completed task.
Add a "Delete" button to allow removal of the task from the completed list.

Deleting Tasks:
Implement the deletion functionality for completed tasks when the "Delete" button is clicked.

Coding Practices:
Use proper event handling (e.g., using preventDefault() to stop form submission from reloading the page).
Write clean, readable code with appropriate comments.
Use functions to separate concerns (e.g., creating a new task element, editing, completing, and deleting tasks).
