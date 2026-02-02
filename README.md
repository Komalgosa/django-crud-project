# Django CRUD Web Application (Student Management System)

## 📌 Project Overview
This project is a basic **Django-based web application** that implements **CRUD (Create, Read, Update, Delete)** operations using a **MySQL database**.  
The application manages student records and demonstrates backend development concepts such as models, views, forms, URL routing, database integration, and template rendering.

The project is designed for **learning purposes, internships, and resume demonstration**.

---

## 🛠️ Tech Stack
- **Programming Language:** Python 3
- **Framework:** Django
- **Database:** MySQL
- **Frontend:** HTML, Bootstrap 5
- **Tools:** VS Code, GitHub
- **Environment:** Virtual Environment (venv)

---

## ✨ Features
- Add new student records
- View all students in a tabular format
- Edit existing student details
- Delete student records
- Form validation using Django ModelForms
- MySQL database integration
- Clean and responsive UI using Bootstrap
- Modular project structure following Django best practices

---

## 📂 Project Structure
django_crud_project/
│
├── venv/ # Virtual environment
│
├── mysite/
│ ├── manage.py
│ ├── mysite/
│ │ ├── settings.py
│ │ ├── urls.py
│ │ └── wsgi.py
│ │
│ └── students/
│ ├── models.py
│ ├── views.py
│ ├── forms.py
│ ├── urls.py
│ └── templates/
│ └── students/
│ ├── base.html
│ ├── list.html
│ └── form.html


---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/django-crud-project.git
cd django-crud-project

### 2️⃣ Create & Activate Virtual Environment
python -m venv venv
venv\Scripts\activate

### 3️⃣ Install Required Packages
pip install django mysqlclient

### 4️⃣ Configure MySQL Database
Create a database:
 CREATE DATABASE studentdb;

Update mysite/settings.py:
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

### 5️⃣ Apply Migrations
cd mysite
python manage.py makemigrations
python manage.py migrate

### 6️⃣ Run the Application
python manage.py runserver

Open browser:
http://127.0.0.1:8000/

## 🧪 CRUD Operations

Create: Add a new student

Read: View student list

Update: Edit student details

Delete: Remove student record

## 📚 Learning Outcomes

Django project and app structure

URL routing and views

Database modeling and migrations

Form handling and validation

Bootstrap UI integration

GitHub version 

---

## Functional Features
- Create student records with form validation
- Display student data in a structured tabular format
- Update existing student information
- Delete student records with confirmation
- Backend validation using Django ModelForms
- Database operations handled using Django ORM
- Responsive and clean UI using Bootstrap

---

## Architecture
- **Models:** Database schema and data handling
- **Views:** Business logic and request handling
- **Templates:** UI rendering using Django templating
- **URLs:** Modular routing with app-level URL configuration
- **Database:** MySQL integration with migrations

---

## Use Case
This application can be extended for:
- College management systems
- Employee or record management portals
- Admin dashboards
- Backend learning projects

---

## Disclaimer
This project is developed for educational and demonstration purposes.