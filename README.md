
# Kanban Task Management Web App

It allows users to manage projects efficiently with features such as creating boards, adding tasks, updating statuses, and drag-and-drop functionality.

## 🚀 Features

📱 **Responsive Design** – Fully responsive layout for desktop, tablet, and mobile views.  
🎯 **CRUD Operations** – Create, Read, Update, Delete for both boards and tasks.  
✅ **Subtasks** – Mark subtasks as complete or incomplete.  
🧠 **Drag and Drop** – Reorder tasks across columns using native drag-and-drop.  
📂 **Dynamic Boards** – Add, rename, or delete boards and columns.  
🔐 **Form Validation** – Built-in validations for forms while adding/editing boards or tasks.  
🌗 **Dark/Light Mode** – Toggle between light and dark themes.  
📚 **Sidebar Toggle** – Collapse or expand the sidebar.

## 📌 Behavior Overview

### Boards
- Switch between boards using the sidebar.
- "Create New Board" opens a modal to add a board and columns.
- Edit or delete existing boards using the options menu.

### Columns
- A board must have at least one column to add tasks.
- Add or remove columns using the edit board modal.

### Tasks
- Add tasks with title, description, subtasks, and status.
- Move tasks between columns by dragging.
- Update task status or edit/delete tasks via modals.

## 🛠 Built With

- React – Frontend library  
- Redux – State management  
- CSS & Flexbox – Layout styling  
- HTML5  
- React Responsive – Media query handling  
- Native Drag and Drop API

## 📚 Useful Resources

- [React Responsive (media queries)](https://www.npmjs.com/package/react-responsive)  
- [W3Schools - Toggle Switch](https://www.w3schools.com/howto/howto_css_switch.asp)  
- [StackOverflow - Prevent event bubbling](https://stackoverflow.com/questions/9183381/how-to-have-click-event-only-fire-on-parent-div-not-children)  
- [Drag and Drop Tutorial (YouTube)](https://www.youtube.com/watch?v=u65Y-vqYNAk)

## 📦 Getting Started

Clone the repo:
```bash
git clone https://github.com/Gattikowsik/Kanban-task-management.git
cd Kanban-task-management
```

Install dependencies:
```bash
npm install
```

Start the development server:
```bash
npm start
```

## 💡 Future Improvements

- User authentication  
- Task deadlines and reminders  
- Integration with external APIs  
- Save data to a backend/database
======
