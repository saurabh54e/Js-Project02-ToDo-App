# JavaScript To-Do App

Project 2 of my 30 JavaScript Projects Challenge.

A fully responsive To-Do application built using HTML, CSS, and Vanilla JavaScript with structured state management and Local Storage persistence.

---

## Features

- Add new tasks
- Delete tasks
- Mark tasks as completed
- Persistent storage using Local Storage
- State-driven rendering without storing raw HTML
- Fully responsive design

---

## Architecture Approach

The application uses a state-driven architecture where tasks are stored as structured data rather than HTML.

Example task data:

```javascript
[
  { text: "Learn JavaScript", completed: false },
  { text: "Build projects", completed: true }
]
```

The UI is dynamically rendered from this data using a `renderTasks()` function.

### Whenever the State Changes

- The tasks array is updated
- Data is saved to Local Storage
- The UI is re-rendered

---

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Local Storage API

---

## What I Learned

- Managing application state using arrays of objects
- Rendering UI dynamically from data
- Using event delegation
- Using `JSON.stringify()` and `JSON.parse()`
- Refactoring from DOM-based to state-based architecture

---

## Live Demo

(https://saurabh54e.github.io/Js-Project02-ToDo-App/)

---

## GitHub Repository

(https://github.com/saurabh54e/Js-Project02-ToDo-App/)

---

## Author

Saurabh Singh

B.Tech CSE — Web Development | UI/UX | Robotics

---

## Challenge Goal

Building 30 JavaScript projects in 30 days to strengthen frontend fundamentals, improve architectural thinking, and build consistently in public.

---

If you like this project, consider giving it a star! ⭐
