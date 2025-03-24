# Task Management System

A simple, minimalistic task management application built with vanilla JavaScript, HTML, and CSS. This application allows users to add, edit, delete, and view tasks, as well as filter and search through their task list.

## Features

### Core Features
- **Add Tasks**: Create new tasks with title, description, due date, and priority
- **View Tasks**: See all tasks in a clean, organized list
- **Edit Tasks**: Modify any task details as needed
- **Delete Tasks**: Remove tasks you no longer need
- **Task Status**: Mark tasks as completed or pending
- **Filter Tasks**: Filter tasks based on their status (all/pending/completed)

### Additional Features
- **Search**: Search for tasks by title or description
- **Due Dates**: Set and track due dates for your tasks
- **Local Storage**: Your tasks persist even after closing the browser
- **Reminder**: Set reminders for tasks that will notify you when the deadline approaches.  

## Installation

1. Clone the repository or download the ZIP file
   ```
   git clone https://github.com/abdullahfirdowsi/I400-TaskManagementSystem.git
   
   ```

2. Navigate to the project directory
   ```
   cd I400-TaskManagementSystem
   ```

3. Open `index.html` in your web browser

No additional installation or dependencies are required! The application runs completely in the browser.

## How to Use

### Put the List Name
1. Fill in the list details in the form at the top
2. Click the "Add" button

### Adding a Task
1. Fill in the task details in the form at the top
2. Click the "Add Task" button

### Editing a Task
1. Click the "Edit" button on any task
2. Modify the details in the form
3. Click "Update Task" to save changes or "Cancel" to discard

### Completing a Task
1. Click the "Complete" button on any task
2. To mark a completed task as pending again, click "Mark as Pending"

### Deleting a Task
1. Click the "Delete" button on any task
2. Confirm the deletion when prompted

### Filtering Tasks
1. Use the "Apply Filters" to filter tasks by status (All/Pending/Completed)

### Searching Tasks
1. Type in the search box to filter tasks by title or description

```
I400-TaskManagementSystem/
├── index.html     # The main HTML structure
├── views.html     # The views HTML structure for Apply Filter & Search Tasks
├── reminders.html # The reminders HTML structure for remaining task sorted by datewise
├── styles.css     # All styling for the application
├── script.js      # JavaScript functionality
└── README.md      # Project documentation
```

## Technologies Used

- **HTML5**: For the structure of the application
- **CSS3**: For styling and responsive design
- **JavaScript (ES6+)**: For all functionality including:
  - DOM manipulation
  - Event handling
  - Local storage for data persistence
  - Array methods for task management
  - Template literals for dynamic HTML

## Browser Compatibility

The application works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## Future Enhancements

Potential future improvements:
- Task categories or tags
- Multiple task lists or projects
- Dark mode theme
- Task reminders or notifications
- Data export/import functionality
- Drag and drop reordering
  
