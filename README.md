# Django Blog Project – Sprint 1

This project is a basic Django blog application created for Sprint 1 of my Systems Integration class. The goal of this sprint was to set up a working Django application, create models and migrations, add initial blog posts through the Django shell, and push the project to GitHub for version control.

## Features
- Django blog application
- Post model with title, content, and timestamp
- Admin panel access for managing posts
- Ability to create and view posts in the browser
- Project configured inside a virtual environment

## Project Setup Instructions

### 1. Create and activate virtual environment
```bash
python3 -m venv venv
source venv/bin/activate

### 2. Install Dependencies
pip install -r requirements.txt

### 3. Run Migrations
python3 manage.py makemigrations
python3 manage.py migrate

### 4. Create a superuser
python3 manage.py createsuperuser

### 5. Start the development server
python3 manage.py runserver

Visit the site at:
http://127.0.0.1:8000

Visit the admin panel at:
http://127.0.0.1:8000/admin

Blog Posts Created

Two sample blog posts were created through the Django shell and admin panel to verify that the Post model and database were set up correctly.

Purpose of Sprint 1

Sprint 1 focused on understanding Django project structure, working with models and migrations, using the Django admin interface, managing a project with Git and GitHub, and preparing a working base for future sprints such as Docker, AWS RDS, and CI/CD. This sprint established the core application that will be integrated and expanded in later modules.
