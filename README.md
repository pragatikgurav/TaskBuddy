# 📝 TaskBuddy

⚡ **A sleek, responsive, and feature-rich React-based task management application designed to help you stay organized and productive.**

---

## 🔗 Live Demo

Deploy your daily productivity with TaskBuddy. Click the button below to see the live application in action:

<div align="center">
  <a href="https://pragatikgurav.github.io/TaskBuddy/" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/🚀%20Launch%20TaskBuddy%20-20232A?style=for-the-badge&logo=react&logoColor=61DAFB&labelColor=111111" alt="Launch Live Demo" height="50" />
  </a>
</div>

---

## 🛠️ Tech Stack & Tools

<div align="left">
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Pages" />
</div>

* **Data Storage:** LocalStorage API
* **Development Environment:** VS Code, Node.js & npm

---

## 🚀 Features

* **Task Input & Validation:** Easily add tasks with built-in protection against empty or duplicate entries.
* **Dynamic Task List:** Mark tasks as complete, delete them, or view your ongoing items in real-time.
* **Task Customization:** Categorize your tasks (*e.g., General, Work, Personal*) and assign priority levels (*High, Medium, Low*).
* **Persistent Storage:** Built-in `localStorage` integration ensures your data survives page refreshes.
* **Live Progress Tracker:** A visual completion tracker that dynamically updates as you complete tasks.
* **Task History:** Review your completed items with options to restore or permanently clear them.
* **Responsive Design:** Fully optimized layout for seamless use across desktops, tablets, and mobile devices.

---

## 📸 Project Screenshots

### ✨ Application Requirements & Interface Plan
*Below is the core requirement overview used for building the application:*

<img src="https://github.com/user-attachments/assets/339d5ed8-dbf2-4a38-93f2-84f4a7592425" width="100%" alt="TaskBuddy Requirements" />

### 📂 File Structure & Initial Architecture
*Setting up the basic project files and component layout:*

<img src="https://github.com/user-attachments/assets/c6f145ee-1e5b-459b-a427-a43dea9f400e" width="100%" alt="File Structure Plan" />

### 💻 Code Implementation (TaskForm Component)
*A deep dive into the form component handling task creation, priority status, and custom category tags:*

<img src="https://github.com/user-attachments/assets/3e00ac0a-1174-475b-b951-1599158886af" width="100%" alt="TaskForm Component Code" />

---

## 📂 Project Architecture

```text
src/
├── components/
│   ├── TaskForm.js        # Handles task input, priorities, and categories
│   ├── TaskList.js        # Displays tasks with complete/delete controls
│   └── ProgressTracker.js # Visual tracker showing completion percentage
├── App.js                 # Main component orchestration
└── index.js               # Application entry point
