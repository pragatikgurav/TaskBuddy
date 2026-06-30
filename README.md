
 # 📝 TaskBuddy

> A sleek, responsive, and feature-rich React-based task management application designed to help you stay organized and productive.

---

## 🔗 Live Demo

✨ **Explore the live app here:** https://pragatikgurav.github.io/TaskBuddy/

---

## 📸 Project Screenshots

### ✨ Application Requirements & Interface Plan
Below is the core requirement overview for building the application:
<img width="592" height="506" alt="Screenshot 2026-06-28 165032" src="https://github.com/user-attachments/assets/339d5ed8-dbf2-4a38-93f2-84f4a7592425" />


---

### 📂 File Structure & Code Implementation
Below is the project architecture and the setup for the `TaskForm` component:
<img width="566" height="695" alt="Screenshot 2026-06-28 165046" src="https://github.com/user-attachments/assets/c6f145ee-1e5b-459b-a427-a43dea9f400e" />

### 📂 File Structure & Code Implementation
Below is the project architecture and the setup for the `TaskForm` component:
<img width="621" height="780" alt="Screenshot 2026-06-28 170225" src="https://github.com/user-attachments/assets/3e00ac0a-1174-475b-b951-1599158886af" />

---

## 🚀 Features

*   **Task Input & Validation:** Easily add tasks with built-in protection against empty or duplicate entries.
*   **Dynamic Task List:** Mark tasks as complete, delete them, or view your ongoing items in real-time.
*   **Task Customization:** Categorize your tasks (e.g., General, Work, Personal) and set priority levels (High, Medium, Low).
*   **Persistent Storage:** Built-in `localStorage` integration ensures your tasks survive page refreshes.
*   **Live Progress Tracker:** A visual completion tracker that dynamically updates as you finish tasks.
*   **Task History:** Review your completed items with options to restore or permanently clear them.
*   **Responsive Design:** Fully optimized layout for desktops, tablets, and smartphones.

---

## 🛠️ Tech Stack & Tools

*   **Frontend Framework:** React.js
*   **Data Storage:** LocalStorage API
*   **Version Control:** Git & GitHub
*   **Development Tools:** VS Code, Node.js & npm

---

## 📂 File Structure

```text
src/
├── components/
│   ├── TaskForm.js        # Handles task input, priorities, and categories
│   ├── TaskList.js        # Displays tasks with complete/delete controls
│   └── ProgressTracker.js # Visual tracker showing completion percentage
├── App.js                 # Main component orchestration
└── index.js               # Application entry point
