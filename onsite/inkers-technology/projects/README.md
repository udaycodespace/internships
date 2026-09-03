# <p align="center">  Inkers Internship Worklog <center> </p>

<p align="center">
  <img src="https://img.shields.io/badge/INTERNSHIP-ENGINEERING-181717?style=for-the-badge&logo=github&logoColor=white" alt="Internship">
  <img src="https://img.shields.io/badge/DEC%201%2C%202025%20%E2%86%92%20MAR%2031%2C%202026-2563EB?style=for-the-badge&logo=calendar&logoColor=white" alt="Duration">
  <img src="https://img.shields.io/badge/4-PROJECTS-7C3AED?style=for-the-badge&logo=github&logoColor=white" alt="Projects">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/JavaScript-20232A?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="JavaScript">
  <img src="https://img.shields.io/badge/Redux%20Toolkit-20232A?style=for-the-badge&logo=redux&logoColor=764ABC" alt="Redux Toolkit">
  <img src="https://img.shields.io/badge/Python-20232A?style=for-the-badge&logo=python&logoColor=3776AB" alt="Python">
  <img src="https://img.shields.io/badge/Frappe-20232A?style=for-the-badge&logo=frappe&logoColor=0089FF" alt="Frappe">
  <img src="https://img.shields.io/badge/MariaDB-20232A?style=for-the-badge&logo=mariadb&logoColor=003545" alt="MariaDB">
  <img src="https://img.shields.io/badge/Linux-20232A?style=for-the-badge&logo=linux&logoColor=FCC624" alt="Linux">
  <img src="https://img.shields.io/badge/Docker-20232A?style=for-the-badge&logo=docker&logoColor=2496ED" alt="Docker">
  <img src="https://img.shields.io/badge/Git-20232A?style=for-the-badge&logo=git&logoColor=F05032" alt="Git">
</p>

<p align="center">
  <sub>December 1, 2025 → March 31, 2026</sub>
</p>

> **Code is where the work starts. Understanding the system is where the learning begins.**

This repository documents the engineering work completed during my internship, from working with Linux and development tools to building React applications, managing state, connecting APIs, and implementing access control.

## 📂 The Work

| Project                              | Stack                       | Focus                               |
| ------------------------------------ | --------------------------- | ----------------------------------- |
| `Systems-Engineering-Practice` 🖥️   | Linux · Bash · Docker · Git | Systems and development environment |
| `Task-Management-RTK` ⚛️             | React · Redux Toolkit       | Application state and UI            |
| `Task-Manager-Frappe-React` 🔗       | React · REST API · Frappe   | Frontend and backend integration    |
| `frappe-role-based-access-system` 🔐 | React · Python · Frappe     | Users, roles, and permissions       |

## 🖥️ Starting at the System Level

Before building applications, I worked with the tools and environments behind them.

| Topic              | What I learned                                     | Where I used it          |
| ------------------ | -------------------------------------------------- | ------------------------ |
| Linux 🐧           | Files, permissions, processes, and system commands | Linux exercises          |
| Bash `</>`         | Shell commands and basic automation                | Command-line tasks       |
| Docker 🐳          | Images, containers, and container workflows        | Development environments |
| Git 🌿             | Commits, branches, and merges                      | Project version control  |
| Troubleshooting 🔧 | Finding issues and working through fixes           | Development environments |

```mermaid
flowchart LR
    Linux["🐧 Linux"] --> Bash["Bash"]
    Bash --> Docker["🐳 Docker"]
    Docker --> Git["🌿 Git"]
    Git --> Troubleshooting["🔧 Troubleshooting"]
```

## ⚛️ Building the Interface

The first application work focused on turning requirements into a usable interface and learning how application state moves through a React application.

| Topic            | What I learned                              | Where I used it    |
| ---------------- | ------------------------------------------- | ------------------ |
| React ⚛️         | Component-based UI development              | Task management UI |
| React Hooks 🪝   | Component state and behaviour               | Forms and UI logic |
| Redux Toolkit 🔄 | Shared application state                    | Task data          |
| Redux Slices 🧩  | Feature-based state organization            | Task state         |
| Redux Store 🗄️  | Centralized application state               | Application state  |
| CRUD ✏️          | Create, read, update, and delete operations | Task operations    |

```mermaid
flowchart LR
    UI["⚛️ React UI"] --> Hooks["🪝 React Hooks"]
    Hooks --> Redux["Redux Toolkit"]
    Redux --> Store["Redux Store"]
    Store --> UI
```

## 🔗 Connecting the Pieces

Once the interface was in place, the work moved into communication between the frontend, backend, API layer, and database.

| Topic             | What I learned                     | Where I used it    |
| ----------------- | ---------------------------------- | ------------------ |
| React ⚛️          | Frontend development               | Task management UI |
| React Hooks 🪝    | State and component logic          | Forms and API data |
| REST API 🔗       | Frontend and backend communication | React → Frappe     |
| CRUD ✏️           | Managing application records       | Task management    |
| Frappe 🟦         | Backend application development    | Task backend       |
| Authentication 🔐 | User authentication                | Application access |
| MariaDB 🗄️       | Backend data storage               | Task records       |

```mermaid
flowchart LR
    User["👤 User"] --> React["⚛️ React"]
    React --> API["🔗 REST API"]
    API --> Frappe["🟦 Frappe"]
    Frappe --> DB["🗄️ MariaDB"]
```

## 🔐 Controlling Access

With users and data connected, the next layer was deciding what each user could see and do.

| Topic              | What I learned                     | Where I used it     |
| ------------------ | ---------------------------------- | ------------------- |
| User Management 👥 | Creating and managing users        | User onboarding     |
| Roles 🛡️          | Assigning access based on roles    | User access         |
| DocPerm 📄         | Configuring document permissions   | Frappe permissions  |
| Authentication 🔐  | Controlling authenticated access   | Login flow          |
| Authorization 🔒   | Controlling actions based on roles | Protected resources |
| Admin Controls ⚙️  | Managing users and permissions     | Admin interface     |

```mermaid
flowchart TD
    User["👤 User"] --> Auth["🔐 Authentication"]
    Auth --> Role["🛡️ Role"]
    Role --> Permission["🔒 Permissions"]
    Permission --> Access{"Access?"}
    Access -->|Yes| Resource["📄 Resource"]
    Access -->|No| Denied["🚫 Access Denied"]
```

## 🔄 How the Work Came Together

Across the projects, the workflow stayed practical: understand the requirement, build the feature, test it, investigate problems, and keep the changes organized.

| Step          | What I learned                          | Where I used it           |
| ------------- | --------------------------------------- | ------------------------- |
| Understand 🧠 | Break requirements into smaller tasks   | All projects              |
| Develop 💻    | Turn requirements into working features | All projects              |
| Test 🧪       | Check expected application behaviour    | React and Frappe projects |
| Debug 🐛      | Trace issues and work through fixes     | Development work          |
| Commit 🌿     | Keep changes organized with Git         | All projects              |
| Document 📝   | Record the work and learning            | This worklog              |

```mermaid
flowchart LR
    Task["📋 Requirement"] --> Build["💻 Build"]
    Build --> Test["🧪 Test"]
    Test --> Debug["🐛 Debug"]
    Debug --> Commit["🌿 Commit"]
    Commit --> Document["📝 Document"]
```

## 📊 Project Status

| Project                              | Status       | What it covered                                  |
| ------------------------------------ | ------------ | ------------------------------------------------ |
| `Systems-Engineering-Practice` 🖥️   | 🟢 Completed | Linux, Bash, Docker, Git, and troubleshooting    |
| `Task-Management-RTK` ⚛️             | 🟢 Completed | React, Hooks, Redux Toolkit, and CRUD            |
| `Task-Manager-Frappe-React` 🔗       | 🟢 Completed | React, APIs, Frappe, authentication, and MariaDB |
| `frappe-role-based-access-system` 🔐 | 🟢 Completed | Users, roles, permissions, and authorization     |

## 👀 Looking Back

The work progressed from the foundations underneath an application to the interface users interact with, the services behind it, and the rules that control access.

That progression is what makes this worklog useful to me. Each project added another piece to the picture.

<p align="center">
  <b>Four projects. One progression: from the environment to the application.</b>
</p>

<p align="center">
  <sub>Inkers Internship · December 1, 2025 → March 31, 2026</sub>
</p>
