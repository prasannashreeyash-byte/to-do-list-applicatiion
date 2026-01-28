# to-do-list-applicatiion

Project Overview

The To-Do List Web Application is a simple yet interactive web-based project designed to help users manage their daily tasks efficiently. The application allows users to add new tasks, mark tasks as completed, and delete tasks when they are no longer needed. It is built using HTML, CSS, and JavaScript, focusing on clean DOM manipulation and basic state management concepts without using any external libraries or frameworks.
This project is ideal for beginners learning front-end web development, as it demonstrates how structure (HTML), presentation (CSS), and behavior (JavaScript) work together to create a dynamic user interface.

Objectives

1.To understand the basic structure of an HTML document
2.To apply CSS styling for better user interface and usability
3.To handle user interactions using JavaScript
4.To dynamically manipulate the DOM without page reloads
5.To manage application state using JavaScript arrays
6.To follow safe and efficient DOM manipulation practices

Technologies Used

1.HTML5 – For creating the basic structure of the application
2.CSS3 – For styling the layout and differentiating input area, task list, completed tasks, and buttons
3.JavaScript (ES6) – For handling user input, events, DOM manipulation, and task management logic

Features

1.Add Tasks: Users can add tasks using the “Add” button or by pressing the Enter key.
2.Task Validation: Empty tasks are not allowed, ensuring meaningful input.
3.Dynamic Task Rendering: Tasks are created dynamically using document.createElement() for safe DOM manipulation.
4.Mark as Completed: Tasks can be marked as completed by clicking on them, visually indicated using a CSS class.
5.Delete Tasks: Each task has a delete button to remove it from the list
6.Event Delegation: Efficient handling of dynamically added elements using a single event listener.
7.State Management: Tasks are stored in a JavaScript array and synchronized with the UI.
8.No Page Reloads: All interactions occur dynamically without refreshing the page.

Working Principle

When a user enters a task and clicks the Add button (or presses Enter), JavaScript captures the input, validates it, and stores it in an array. The task list is then re-rendered dynamically. Clicking on a task toggles its completed state, while clicking the delete button removes the task from the array and updates the UI accordingly. Console logs are used during development for debugging and testing purposes.

How to Run the Project

1.Create a file named index.html
2.Copy and paste the complete project code into the file
3.Open the file in any modern web browser (Chrome, Edge, Firefox)
4.Start adding and managing tasks

Output:
screenshot:
screenshot:
