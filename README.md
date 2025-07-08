# React To-Do List

This is a basic To-Do List app built using React. It lets you add tasks, mark them as completed, and delete them. All your tasks are saved in your browser using localStorage, so they stay even after refreshing the page.

## Features

- Add new tasks
- Mark tasks as done (with a tick and line-through)
- Delete tasks
- Data saved using localStorage
- Simple and clean design

## How to Run

1. Clone this repository or download the project files.
2. Open a terminal in the project folder.
3. Run:

```bash
npm install
npm start
````

4. Open your browser and go to `http://localhost:3000`.

## Folder Structure

* `components/` – Contains `Todo.js` and `TodoItems.js`
* `CSS/` – Contains the styles for the components
* `Assets/` – Contains the icons used (tick, not-tick, cross)
* `App.js` – Main app file
* `index.js` – Entry point for React

## Notes

* This app uses React hooks like `useState`, `useRef`, and `useEffect`.
* Make sure the images are in the correct path (`/components/Assets/`).
* You can improve the app by adding features like edit task, due date, filters, etc.
