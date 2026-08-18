# Student Management System

A web-based **Student Management System** developed using **Python and Django**. The application provides a simple interface to manage student information and perform basic CRUD operations.

**Live Demo:** https://student-management-system-1-h22s.onrender.com/

## 🚀 Features

* Add new students
* View student details
* Delete student records
* Manage student information through Django
* SQLite database integration
* Simple and responsive web interface
* Django Admin Panel support

## 🛠️ Technologies Used

* **Python**
* **Django**
* **SQLite3**
* **HTML5**
* **CSS3**
* **JavaScript**
* **Git & GitHub**

## 📁 Project Structure

```text
Student-Management-System/
│
├── manage.py
├── db.sqlite3
├── StudentManagementSystem/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── student/
│   ├── migrations/
│   ├── templates/
│   ├── admin.py
│   ├── models.py
│   ├── views.py
│   └── urls.py
│
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/Siri-kr/Student-Management-System.git
```

### 2. Open the project

```bash
cd Student-Management-System
```

### 3. Install Django

```bash
pip install django
```

### 4. Apply migrations

```bash
python manage.py migrate
```

### 5. Run the development server

```bash
python manage.py runserver
```

### 6. Open in browser

Open:

```text
http://127.0.0.1:8000/
```

## 🔐 Django Admin

To create an admin account:

```bash
python manage.py createsuperuser
```

Then open:

```text
http://127.0.0.1:8000/admin/
```

## 🎯 Purpose

The project demonstrates the development of a basic database-driven web application using the **Django framework**, including models, views, templates, URL routing, database operations, and administrative functionality.

## 🔮 Future Enhancements

* Student search and filtering
* Student update/edit functionality
* Authentication and authorization
* Pagination
* Improved UI/UX
* REST API integration
* Student attendance management

## 👩‍💻 Author

**Siri K R**

GitHub: https://github.com/Siri-kr
