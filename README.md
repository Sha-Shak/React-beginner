# Task Manager App - React Learning Exercise

## 🚀 Overview
Welcome to the **Task Manager App** learning exercise! This step-by-step guide will help you learn **React fundamentals** while building a functional task manager application. Each milestone introduces a new concept, from **state management and props** to **React Router and Context API**.

---

## 🛠️ Tech Stack
- **React (Vite + TypeScript)**
- **TailwindCSS**
- **React Router**
- **Context API**
- **Local Storage**
- **Framer Motion (Optional)**

---

## 📌 Milestone 1: Project Setup & Basic Components
### ✅ Steps:
1. Install Node.js and create a React app using Vite:
   ```sh
   npm create vite@latest task-manager
   cd task-manager
   npm install
   npm run dev
   ```
2. Install dependencies:
   ```sh
   npm install tailwindcss react-router-dom
   npx tailwindcss init -p
   ```
3. Configure Tailwind in `tailwind.config.js`.
4. Create a **basic UI**:
   - Add a **Header** (`Task Manager`).
   - Create a `TaskList.tsx` component (static task list).
   - Create a `Task.tsx` component (shows task details).

---

## 📌 Milestone 2: Props, State, and Event Handling
### ✅ Steps:
5. Create a **Task interface** (TypeScript).
6. Pass task data from `TaskList.tsx` to `Task.tsx` using **props**.
7. Implement **useState** to manage tasks dynamically.
8. Add a **form** (`AddTask.tsx`) with input fields for task name & description.
9. Handle form submission & update task list state.

---

## 📌 Milestone 3: Conditional Rendering & Props Drilling
### ✅ Steps:
10. Implement a "Mark as Done" button in each task.
11. Style completed tasks differently (gray background, strikethrough text).
12. Implement a "Delete Task" button.
13. Use props drilling to pass functions down to `Task.tsx`.
14. Add filtering buttons: **All, Completed, Pending** tasks.

---

## 📌 Milestone 4: Lifting State Up & Context API
### ✅ Steps:
15. Move state from `TaskList.tsx` to `App.tsx` (lifting state up).
16. Use React **Context API** to manage global state (`TaskContext.tsx`).
17. Refactor components to consume context instead of prop drilling.
18. Implement a **dark mode toggle** using Context API.

---

## 📌 Milestone 5: React Router & Dynamic Pages
### ✅ Steps:
19. Install React Router (`react-router-dom`).
20. Create two pages: **Task List** (`/`) & **Task Details** (`/task/:id`).
21. Implement navigation using `Link`.
22. Display task details dynamically using `useParams()`.
23. Add a "Back to Home" button on the details page.

---

## 📌 Milestone 6: Custom Hooks & Local Storage
### ✅ Steps:
24. Store tasks in **Local Storage** so they persist after refresh.
25. Create a **custom hook** `useTasks.tsx` for managing task operations.
26. Implement a **Snackbar Notification** (`Task added!`, `Task deleted!`).

---

## 📌 Milestone 7: Advanced Features & Deployment
### ✅ Steps:
27. Implement a **drag-and-drop** feature to reorder tasks (`react-beautiful-dnd`).
28. Add animations with `framer-motion`.
29. Deploy the app using **Vercel** or **Netlify**.
30. Celebrate! 🎉

---

## 🌟 End Goal
After completing all milestones, you will have a **fully functional React project** with:
✅ Component-based architecture  
✅ Props & state management  
✅ Context API for global state  
✅ React Router for navigation  
✅ Custom hooks for reusability  
✅ Persistent data with Local Storage  
✅ Modern UI with TailwindCSS  
✅ Responsive & interactive features  

Start coding and have fun! 🚀

