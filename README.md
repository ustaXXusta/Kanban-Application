# Kanban Application

Kanban is an Electron-based desktop application that allows you to organize your tasks visually. This application allows you to manage your projects using the Kanban methodology and organizes your workflow by separating tasks into columns such as "To Do", "In Progress" and "Done". It also offers the ability to automatically detect the Kanban folder created by the application and move the Kanban file inside it to the Applications folder of your system.

# Project Purpose

This project was developed to help users manage their tasks effectively. The Kanban methodology aims to increase productivity by visualizing the workflow. Developed using Electron, this application offers cross-platform support (Windows, macOS, Linux) and facilitates task management with a user-friendly interface. It also simplifies the installation process by automatically moving the Kanban file inside the Kanban folder created by the application to the Applications folder.
# Features
- Visual Kanban Board: Manage tasks by dragging and dropping between columns.

- User Friendly Interface: Easy to use with a simple and modern design.

Flexible Task Management: Add, edit and delete tasks.

# Requirements
- Node.js (v14 or later)

- npm (included with Node.js)

- Electron (automatically installed as part of project dependencies)

# Installation

1) Clone Repo
```bash
git clone https://github.com/ustaXXusta/Kanban-Application
```
2) Go to file
```bash
cd Kanban-Application
```
3) Check the main dependencies (second bash if not exist) 
```bash
node -v
npm -v
```
4) Install dependencies to project:
```bash
npm install
```
5) Add electron and electron-packager packages to project:
```bash
npm install electron --save-dev
npm install electron-packager --save-dev
```
6) Run build
```bash
npx electron-packager . Kanban --platform=darwin --arch=x64 --icon=icon.icns --overwrite
```
7) After the build is complete, open the folder and run your application (Kanbanx64)

# Usage
- When you start the application, a Kanban board opens.

- To add a task, click the "New Task" button and enter the task details.

- Move tasks between columns with one click to the next step.

- Use the button at the bottom right to edit or delete tasks (deletes all).
