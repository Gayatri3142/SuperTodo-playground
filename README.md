# SuperTodo – Task Management Application

A modern, responsive Todo application built with **React 19 and Vite** to help users organize tasks, manage priorities, track deadlines, and improve productivity.

🔗 **Live Demo:** https://todoplayground.vercel.app/

📂 **GitHub Repository:** https://github.com/Gayatri3142/SuperTodo-playground

---

## ✨ Features

- **Task Management:** Create, edit, and delete tasks.
- **Task Details:** Add titles and descriptions to tasks.
- **Priority Management:** Assign High, Medium, and Low priority levels.
- **Due Dates:** Set deadlines for individual tasks.
- **Subtasks:** Break larger tasks into smaller activities and track their completion progress.
- **Task Status:** Mark tasks as Pending or Completed.
- **Search Tasks:** Quickly find tasks using the search functionality.
- **Filter Tasks:** View All, Pending, or Completed tasks.
- **Sort Tasks:** Organize tasks by priority and creation date.
- **Date-based Grouping:** Organize tasks into Overdue, Today, This Week, Later, and No Date categories.
- **Clear Completed Tasks:** Remove completed tasks when no longer needed.
- **Dark & Light Mode:** Switch between themes.
- **Local Storage:** Automatically persist tasks in the browser.
- **Smooth Animations:** Enjoy interactive transitions and animations.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| React 19 | Frontend UI development |
| Vite | Development server and build tool |
| JavaScript (ES6+) | Application logic |
| Tailwind CSS 4 | Styling and responsive layouts |
| Radix UI | Accessible UI components |
| Framer Motion | Animations and transitions |
| Lucide React | Icons |
| date-fns | Date formatting and date operations |
| React Day Picker | Calendar and date selection |
| Local Storage | Client-side data persistence |
| Vercel | Application deployment |
| Git & GitHub | Version control and source code management |

---

## 📸 Application Preview

Try the live application:

**https://todoplayground.vercel.app/**

---

## 📁 Project Structure

```text
SuperTodo-playground/
│
├── public/
│
├── src/
│   ├── components/
│   │   ├── ui/
│   │   ├── Sidebar.jsx
│   │   ├── TodoDetail.jsx
│   │   ├── TodoInput.jsx
│   │   ├── TodoInputDialog.jsx
│   │   ├── TodoItem.jsx
│   │   └── TodoList.jsx
│   │
│   ├── hooks/
│   │   └── useTodos.js
│   │
│   ├── providers/
│   │   ├── theme-provider.jsx
│   │   └── features/
│   │
│   ├── lib/
│   │   └── utils.js
│   │
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── .gitignore
├── index.html
├── package.json
├── package-lock.json
├── vite.config.js
└── README.md
```

---

## 🚀 Getting Started

Follow these instructions to run the project locally.

### Prerequisites

Make sure you have installed:

- [Node.js](https://nodejs.org/)
- npm (comes with Node.js)
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/Gayatri3142/SuperTodo-playground.git
```

### 2. Navigate to the Project Directory

```bash
cd SuperTodo-playground
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Start the Development Server

```bash
npm run dev
```

### 5. Open in Browser

Visit:

```text
http://localhost:5173
```

---

## 📦 Available Scripts

| Command | Description |
|---|---|
| `npm install` | Install project dependencies |
| `npm run dev` | Start the development server |
| `npm run build` | Create a production build |
| `npm run preview` | Preview the production build locally |
| `npm run lint` | Run ESLint checks |

---

## 🏗️ Application Architecture

The project follows a component-based architecture with separation of concerns.

- **Components:** Handle reusable UI elements and task presentation.
- **Custom Hooks:** Manage task state and business logic using `useTodos`.
- **Providers:** Manage application-wide theme settings.
- **Local Storage:** Persist task information in the browser.
- **Derived State:** Handle task filtering, sorting, and counts.

---

## 🌐 Deployment

This application is deployed using **Vercel**.

🔗 **Live Application:** https://todoplayground.vercel.app/

The project is connected to GitHub for version control and deployment updates.

---

## 🔮 Future Enhancements

- User authentication and personalized task management.
- Backend integration with REST APIs.
- Cloud-based database storage.
- Drag-and-drop task organization.
- Task reminders and notifications.
- Unit and integration testing.
- Improved accessibility.

---

## 👩‍💻 Author

**Gayatri**

GitHub: [@Gayatri3142](https://github.com/Gayatri3142)

---

⭐ If you find this project useful, consider giving the repository a star!
