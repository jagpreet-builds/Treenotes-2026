# TreeNotes Frontend

TreeNotes is an AI-powered linked note-taking web application that combines the Cornell Note-Taking Method with semantic search, concept extraction, and graph-based knowledge visualisation.

This repository contains the React frontend for the TreeNotes CSIT321 Capstone Project.

## Project Features

* User login interface
* User dashboard
* Create and manage notes
* Cornell-style note workspace
* Raw notes panel
* Knowledge graph visualisation panel
* Summary panel
* Search and navigation
* Responsive user interface
* Integration-ready structure for backend APIs

## Technology Stack

* React
* Vite
* JavaScript
* HTML
* CSS
* React Router
* Git and GitHub

## Project Structure

```text
src/
  components/
    layout/
    notes/
    shared/

  pages/
    LoginPage.jsx
    DashboardPage.jsx
    HomePage.jsx
    NotesPage.jsx
    SettingsPage.jsx

  data/
    mockNotes.js

  App.jsx
  main.jsx
  index.css
```

## Installation

Clone the repository:

```bash
git clone https://github.com/jagpreet-builds/Treenotes-2026.git
```

Open the project folder:

```bash
cd treenotes-frontend
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

The project will usually run at:

```text
http://localhost:5173
```

## Development Workflow

Create a feature branch before starting work:

```bash
git checkout -b feature/login-page
```

Commit your changes:

```bash
git add .
git commit -m "Build login page"
```

Push the branch:

```bash
git push origin feature/login-page
```

Create a pull request before merging changes into the main branch.

## Frontend Pages

* Login
* Dashboard
* Home
* Notes workspace
* Settings
* Search
* Knowledge graph view

## Current Status

The high-fidelity interface designs have been completed in Figma.

The current development phase focuses on converting the approved designs into responsive React components using mock data before backend API integration.

## Team

TreeNotes CSIT321 Capstone Development Team

Frontend Contributors:

* Jagpreet Singh
* David Hanna

## License

This project was developed for academic purposes as part of the University of Wollongong CSIT321 Capstone Project.
