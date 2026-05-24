# ✦ Taskflow — JavaScript To-Do App

A fully interactive task management app built with vanilla HTML, CSS, and JavaScript. No libraries, no frameworks — just core JS concepts applied to a real-world UI.

---

## 🔗 Live Demo

[View Live →](https://priyankasahoo2712-cmyk.github.io/taskflow-todo)

---

## ✨ Features

- **Add tasks** with priority (High / Medium / Low) and category (Work / Personal / Learning / Health)
- **Complete tasks** — click the circle to mark done, with visual strikethrough
- **Delete tasks** — smooth slide-out animation on removal
- **Filter tasks** — by All, Pending, Done, High Priority, Work, Learning
- **Live stats** — total, completed, and pending count updates instantly
- **Animated entrance** — tasks slide in smoothly when added
- **Persistent default tasks** — pre-loaded to demonstrate all features

---

## 🛠️ Built With

| Technology | Usage |
|---|---|
| HTML5 | Semantic structure |
| CSS3 | Flexbox, animations, custom properties, responsive design |
| JavaScript (ES6+) | DOM manipulation, array methods, event handling |
| Google Fonts | Plus Jakarta Sans |

---

## 📐 JavaScript Concepts Used

- **Arrays** — tasks stored and managed as an array of objects
- **Objects** — each task is an object `{ id, text, done, priority, category }`
- **Functions** — `addTask()`, `toggleTask()`, `deleteTask()`, `render()`, `setFilter()`
- **Conditionals** — `if/else` for input validation, `switch` for filter logic
- **Loops** — `.map()`, `.filter()`, `.forEach()` to render and manage tasks
- **Strings** — template literals for dynamic HTML generation
- **DOM Events** — `onclick`, `addEventListener` for keyboard (Enter key) support
- **Spread operator** — immutable task updates with `{ ...t, done: !t.done }`

---

## 🧠 How It Works

```
User types task → addTask() runs → task object pushed to array
                                          ↓
                                     render() called
                                          ↓
                          getFiltered() applies current filter
                                          ↓
                           tasks.map() generates HTML string
                                          ↓
                            innerHTML updated in the DOM
```

---

## 📁 Project Structure

```
taskflow-todo/
│
├── index.html       # App HTML + CSS + JavaScript in one file
└── README.md        # Project documentation
```

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/priyankasahoo2712-cmyk/taskflow-todo.git
   ```

2. Open `index.html` in your browser — works instantly, no setup needed!

---

## 🎯 What I Learned

- Manipulating the DOM dynamically using `innerHTML` and event listeners
- Managing application state with a JavaScript array
- Using `.map()` and `.filter()` to render and filter UI from data
- Writing clean, readable functions for each app action
- Handling user input validation and keyboard events
- Creating smooth CSS animations triggered by JavaScript class changes

---

## 👩‍💻 Author

**Priyanka Sahoo**
Frontend Developer
📧 priyankasahoo2712@gmail.com
🔗 [GitHub](https://github.com/priyankasahoo2712-cmyk)
