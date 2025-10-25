# NoteTaking
📝 React Note-Taking App

A clean and simple note & project management app built with React.
This app lets users create multiple projects, add and delete tasks within each project, and easily switch between projects using a sidebar interface. It’s built entirely with React hooks and state management — no external database or frameworks.

🌟 Features

✅ Create and manage multiple projects
✅ Add and remove tasks for each project
✅ Dynamic sidebar for quick project navigation
✅ Responsive and minimalist UI
✅ Built with React Hooks (useState)
✅ Easy to extend and customize

🧠 How It Works

The app maintains a single state object with three properties:

projects: stores all created projects

tasks: stores all tasks linked to projects

selectedProjectId: determines which project’s tasks are displayed

Each major feature (project creation, selection, and deletion) updates this central state, ensuring smooth and predictable behavior across components.

🧩 Components

ProjectsSidebar: Displays the list of projects and allows switching between them.

NewProject: Handles creation of new projects.

SelectedProject: Shows the current project’s details and related tasks.

NoProjectSelected: Displayed when no project is currently active.

🛠️ Tech Stack

React (Vite or CRA)

JavaScript (ES6+)

CSS (custom styling)

🚀 Getting Started
1️⃣ Clone the repository
git clone https://github.com/yourusername/react-note-taking-app.git
cd react-note-taking-app

2️⃣ Install dependencies
npm install

3️⃣ Run the app
npm run dev


Then open http://localhost:5173/
 (if using Vite) in your browser.

💡 Future Improvements

Add data persistence (localStorage or database)

Edit existing tasks and projects

Improve mobile UI and animations

Dark mode toggle

👨‍💻 Author

Justin Dawson Groom
A self-taught front-end developer passionate about building clean, functional, and user-friendly interfaces.
