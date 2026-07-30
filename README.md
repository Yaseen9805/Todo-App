# Todo App

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript&logoColor=black)

## Short description

A responsive todo app built with plain HTML, CSS, and JavaScript. Add tasks with an optional date and description, edit or delete them later, and everything is saved in the browser with localStorage.

## Technologies

HTML5, CSS3, JavaScript (DOM manipulation, localStorage)

## Features

- Add new tasks with a required title, plus an optional date and description
- Edit an existing task's details
- Delete tasks you no longer need
- A confirmation dialog before discarding unsaved changes
- All data persists across page reloads using localStorage

## The process

This went a step beyond a basic add/delete list by supporting full editing and optional fields per task, which meant the form had to handle both "creating a new task" and "editing an existing one" without becoming two separate pieces of code. Adding a confirmation step for unsaved changes was a smaller but useful addition, so closing the form accidentally doesn't silently lose whatever was typed.

## What I learned

- Structuring a form that can both create and edit an item, depending on context
- Validating required vs. optional fields before saving
- Persisting structured task data (not just plain strings) to localStorage as JSON
- Prompting for confirmation before a potentially destructive action like discarding changes

## How it can be improved

- Add the ability to mark tasks as completed
- Add filters to view completed vs. pending tasks
- Support drag-and-drop reordering of tasks
- Add search to quickly find a specific task

## How to run the project

1. Clone the repo
2. Open `index.html` directly in your browser
