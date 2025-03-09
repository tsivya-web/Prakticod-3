# Praktikod 3
Daily Tasks App

Overview

The Daily Tasks App is a task management application built with React for the frontend and Node.js with an SQL database for the backend. It provides a public page accessible to all users and a private page accessible only to registered users.

Features:

Public page accessible to all users.

Private page accessible only to authenticated users.

User authentication with JWT tokens.

Secure login and registration system.

Tokens are stored in local storage to minimize server requests.

Backend built with Node.js.

SQL database for storing user information and tasks.

Usage:

Open the public page.

Register or log in to access the private page.

Upon login, a JWT token is issued and stored in local storage.

The token is sent with each request to the backend to verify authentication.

If the token is invalid or tampered with, the user is redirected to the login page.

Technologies Used

React (Frontend)

Node.js (Backend)

SQL (Database)

JWT (Authentication)
