Mark Lab – Django CRM Application

Description:
Mark Lab is a modular Django-based CRM (Customer Relationship Management) system used to manage customers, CRM workflows, and admin operations. It follows a clean project structure with separate apps for better scalability and learning.

Key Features:

1-Separate modular apps:
  • adminapp – Admin operations
  • crmapp – CRM core functions
  • customerapp – Customer management
2-Built with Django best practices
3-Uses Django ORM
4-Supports media file handling
5-Uses SQLite3 as the default database

Tech Stack:
Python
Django
HTML, CSS, JavaScript
SQLite3

Project Structure:

Mark_Lab/
adminapp/
crmapp/
customerapp/
crmproject/
media/
db.sqlite3
manage.py
.gitignore
README.md

How to Run the Project Locally:

Step 1: Clone the repository
git clone https://github.com/Mohammad-Rashid007/Mark_Lab.git

Step 2: Go inside the project folder
cd Mark_Lab

Step 3: Install Django (if not installed)
pip install django

Step 4: Run migrations
python manage.py migrate

Step 5: Start the development server
python manage.py runserver

Step 6: Open in browser
http://127.0.0.1:8000/

Usage:
Use the Django admin panel to manage customer data and CRM features.
Each app (adminapp, crmapp, customerapp) handles a separate section of the CRM.

Contributing:

Fork the repository
Create a new branch
Commit your changes
Push to your branch
Open a pull request

License:
MIT License

Copyright (c) 2025 Mohammad Rashid

Thank You:
Thank you for exploring Mark Lab. Feel free to reach out if you want help improving the project.
