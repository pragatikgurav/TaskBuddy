# 📝 TaskBuddy

> A sleek, responsive, and feature-rich React-based task management application designed to help you stay organized and productive.

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
