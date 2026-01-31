
"Ditch the WhatsApp Chaos"

PG-PMS (Project Management System) is a high-end, developer-centric workspace built to solve the fragmentation of team collaboration during high-stakes projects like the Smart India Hackathon (SIH).

Most tools require expensive hosting or complex databases. PG-PMS is different. It is 100% serverless, using the GitHub REST API to turn your repository's tasks.json into a live, version-controlled database.

✨ Key Features

📊 Real-time Progress Visualizer: A dynamic dashboard calculating project health based on weighted task completion.

📋 Kanban Workflow: Manage tasks through four stages: To-Do, In Progress, Review, and Done.

🛡️ Team Roles & Expertise: Gamified profiles with Gold, Silver, Bronze, and Wood badges to showcase seniority and skills.

📝 Owner-Locked Sticky Notes: A collaborative "Post-it" board for quick team updates. Notes are locked to their creator for security.

📁 Integrated Documentation: A central hub for all project assets, Google Drive links, and Figma files.

🌙 Professional Dark Mode: A midnight-themed UI optimized for long coding sessions, featuring an auto-inverting logo mechanism.

📜 Automated Audit Log: A transparent "Who did what and when" feed powered by GitHub's commit history.

🛠️ The "Rocket Science" Architecture

This project operates without a traditional backend.

Frontend: Vanilla JS + Tailwind CSS (Hosted on GitHub Pages).

Database: tasks.json residing within this repository.

API: Every UI interaction (like moving a task) triggers a GitHub REST API call.

Security: Secured via Personal Access Tokens (PAT), ensuring only authorized collaborators can modify the project state.

🚀 Quick Setup (3 Minutes)

Fork this Repository and enable GitHub Pages in the settings.

Update Config: Open index.html and set:

const REPO_OWNER = "your-username";


Initialize Data: Create a tasks.json file in the root with:

{ "tasks": [], "logs": [], "docs": [], "notes": [], "roles": [] }


Get your Passcode: Generate a GitHub Fine-grained Token with Contents: Read & Write permissions.

Login and Collaborate!

🎨 Design Philosophy

Typography: Poppins (Professional & Clean)

Palette: Minimalist White / Midnight Dark (#1f1f1f)

Shapes: Capsule-styled components for a modern "Studio" vibe.

<p align="center">
Made with ❤️ by <b>Parthiv</b> & Team
</p>
