📓 Notes App (Django + React Full-Stack)

A full-stack Notes App built with Django (backend) and React (frontend) that allows users to register, login, and manage their notes securely. Users can add, modify, and delete notes, and the application implements protected routes to ensure that only authenticated users can access their notes.

🚀 Features

User Authentication

Registration page to create a new account.

Login page for existing users.

Protected routes to restrict access to notes only for authenticated users.

Notes Management

Add a new note.

Edit/update existing notes.

Delete notes.

Navigation Pages

Home Page – overview of all notes.

Not Found Page – handles invalid URLs gracefully.

Backend

Django REST Framework (DRF) for APIs.

Models for storing notes and users.

Views for handling CRUD operations on notes.

URL routing for API endpoints.

Frontend

React with functional components and hooks.

React Router for navigation and protected routes.

Responsive UI for notes management.

🛠️ Technology Stack
Layer	Technology / Library
Backend	Django, Django REST Framework
Frontend	React, React Router, Axios
Database	SQLite (default) / PostgreSQL option
Authentication	JWT / Token-based auth (Django REST Framework)
