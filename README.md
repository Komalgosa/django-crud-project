# 🎓 Django CRUD Web Application
## Student Management System

---

## 📌 Project Overview

This project is a Django-based CRUD (Create, Read, Update, Delete) web application integrated with a MySQL database.  
It manages student records and demonstrates core backend development concepts such as:

- Django project & app structure
- Models and ORM
- Views and URL routing
- Forms and validation
- Template rendering
- Database integration

The project is ideal for learning, internships, academic submissions, and resume projects.

---

## 🛠️ Tech Stack

| Category | Technology |
|--------|------------|
| Programming Language | Python 3 |
| Framework | Django |
| Database | MySQL |
| Frontend | HTML, Bootstrap 5 |
| Tools | VS Code, Git, GitHub |
| Environment | Virtual Environment (venv) |

---

## ✨ Features

- Add new student records
- View all students in a structured table
- Update existing student details
- Delete student records with confirmation
- Django ModelForm-based validation
- MySQL database integration
- Clean and responsive UI using Bootstrap
- Modular Django project structure

---

## 📂 Project Structure

django_crud_project/
│
├── venv/                     # Virtual environment
│
├── mysite/
│   ├── manage.py
│   │
│   ├── mysite/
│   │   ├── settings.py
│   │   ├── urls.py
│   │   └── wsgi.py
│   │
│   └── students/
│       ├── models.py
│       ├── views.py
│       ├── forms.py
│       ├── urls.py
│       └── templates/
│           └── students/
│               ├── base.html
│               ├── list.html
│               └── form.html

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository
git clone https://github.com/your-username/django-crud-project.git  
cd django-crud-project

---

### 2️⃣ Create & Activate Virtual Environment
python -m venv venv  

Windows:
venv\Scripts\activate  

---

### 3️⃣ Install Required Packages
pip install django mysqlclient

---

### 4️⃣ Configure MySQL Database

Create database:
CREATE DATABASE studentdb;

Update `mysite/settings.py`:

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'studentdb',
        'USER': 'django_user',
        'PASSWORD': 'your_password',
        'HOST': 'localhost',
        'PORT': '3306',
    }
}

---

### 5️⃣ Apply Migrations
cd mysite  
python manage.py makemigrations  
python manage.py migrate  

---

### 6️⃣ Run the Application
python manage.py runserver  

Open browser:
http://127.0.0.1:8000/

---

## 🧪 CRUD Operations

- Create: Add a new student record
- Read: View all student records
- Update: Edit student information
- Delete: Remove student record

---

## 📚 Learning Outcomes

- Django project and app architecture
- URL routing and request handling
- Database modeling and migrations
- Form handling and validation
- Bootstrap UI integration
- GitHub version control workflow

---

## 🧩 Functional Components

- Django Models for database schema
- Views for business logic
- Templates for UI rendering
- App-level URL routing
- ORM-based database operations

---

## 🏗️ Application Architecture

- Models: Define database tables and relationships
- Views: Handle application logic
- Templates: Render frontend UI
- URLs: Map routes to views
- Database: MySQL with Django ORM

---

## 🔍 Use Cases

This application can be extended for:
- College or school management systems
- Employee or record management portals
- Admin dashboards
- Backend learning projects

---

## ⚠️ Disclaimer

This project is developed for educational and demonstration purposes only.
