# Authentication-Project
A Node.js authentication system with sessions, password hashing, and Google OAuth integration

The Authentication Project is a web application that implements secure user authentication using multiple strategies. The goal is to demonstrate how to protect sensitive routes, manage user sessions, and allow sign-in through both traditional credentials and third-party OAuth providers.

Features

User Registration & Login
Secure sign-up and login using username and password (with hashing via bcrypt).
Session Management
Users remain logged in using express-session and cookies.
OAuth Integration
Login using Google OAuth 2.0, enabling quick and secure third-party authentication.
Protected Routes
Only authenticated users can access certain pages (e.g., dashboard).
Logout Functionality
Users can securely log out and end their session.

🛠️ Tech Stack

Backend: Node.js, Express.js
Database: postgres 
Authentication: Passport.js (Local Strategy + Google OAuth 2.0 Strategy)
Security: bcrypt for password hashing, environment variables for secrets
Frontend: EJS (templating) with Bootstrap for styling

Learning Outcomes

Understand how authentication works in real-world apps.
Learn how to protect sensitive routes and manage sessions.
Gain hands-on experience with Passport.js strategies.
Implement environment variables (.env) to keep secrets safe
