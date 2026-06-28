# ✅ Todo List

A simple todo list app built with HTML and vanilla JavaScript — items persist 
across page reloads using the browser's localStorage API.

![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## Features
- Add new items to the list via text input and button click
- Delete individual items with a per-item Delete button
- Items persist across page reloads using `localStorage`
- Input validation — alerts if trying to add an empty item
- Items rendered dynamically into the DOM using `createElement` and `appendChild`
- Auto-loads saved items on page load via `DOMContentLoaded`

## Tech Stack
| Layer | Technology |
|-------|------------|
| Structure | HTML5 |
| Logic | Vanilla JavaScript (ES6) |
| Storage | Browser localStorage API |

## Setup
```bash
git clone https://github.com/Zemoik/Todo-List.git
cd Todo-List
open main.html
```
No dependencies, no build step, no internet connection required.

## Project Structure
```
Todo-List/
├── main.html    # Markup — title, items container, input, add button
├── index.js     # Add/remove/render logic, localStorage persistence
└── README.md
```

## What I Learned
- Persisting data in the browser using `localStorage.setItem` / `getItem` with JSON serialization
- Dynamically creating and appending DOM elements with `createElement`
- Managing array state and re-rendering the UI on every change
- Using `Object.entries()` to get both index and value while iterating an array
- Handling input validation with early returns and user alerts
- Loading saved state on page load using the `DOMContentLoaded` event

## Author
**Dev Patel** — [LinkedIn](https://www.linkedin.com/in/dev--patel--/) · [GitHub](https://github.com/Zemoik)
