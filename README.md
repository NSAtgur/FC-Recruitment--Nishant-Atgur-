# Role-Based Student Management System

A Flask-based web application with role-based access control and CRUD functionality.

## Features
- User authentication
- Role-based permissions
- Student CRUD operations
- Server-side rendered templates
- Deployed on Render

Live Demo: <https://python-projects-pf6q.onrender.com>

Deployment
1. Push the project to GitHub
2. Create a new Web Service on Render
3. Select the GitHub repository
4. Set build command:
   pip install -r requirements.txt
5. Set start command:
   gunicorn app:app
6. Add environment variables (if any)
7. Deploy
