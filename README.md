# 📝 To-Do List API (Django REST Framework)

A simple REST API backend built using Django and Django REST Framework to manage personal to-do tasks.  
Users can create, read, update, and delete tasks. This project is the first step in building a fully deployed backend application.

---

## 🚀 Features
- Create and manage tasks
- Mark tasks as complete/incomplete
- Django Admin panel support
- REST API endpoints tested using Postman

---

## 🛠 Tech Stack
- Python
- Django
- Django REST Framework
- SQLite (default database)

---

## 📦 Setup Instructions

```bash
git clone <repository-url>
cd todo_api
python -m venv env
env\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
