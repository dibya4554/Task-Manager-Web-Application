# 🚀 Task Manager Web Application (Django)

## 📌 Overview

This is a web-based Task Manager application built using the **Django framework**. The system allows users to create, manage, and track tasks efficiently with a structured backend and admin interface.

---

## 🛠️ Tech Stack

* Python
* Django
* SQLite
* Postman (for API testing)

---

## 🔑 Features

* Create new tasks
* View all tasks
* Update existing tasks
* Delete tasks
* Task fields:

  * Title
  * Description
  * Deadline
  * Priority
  * Completion Status
* Django Admin panel for management
* Clean and scalable backend architecture

---

## 📂 Project Structure

```bash
taskmanager_pro/
│
├── config/        # Project settings
├── tasks/         # Main app
│   ├── models.py
│   ├── views.py
│   ├── admin.py
│
├── db.sqlite3
└── manage.py
```

---

## ⚙️ Setup Instructions

### 🔹 Clone Repository

```bash
git clone <your-repo-link>
cd taskmanager_pro
```

---

### 🔹 Create Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate   # Windows
```

---

### 🔹 Install Dependencies

```bash
pip install django
```

---

### 🔹 Run Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

---

### 🔹 Run Server

```bash
python manage.py runserver
```

👉 Open in browser:

```
http://127.0.0.1:8000/tasks/
```

---

## 🧪 API Endpoints

| Method | Endpoint       | Description   |
| ------ | -------------- | ------------- |
| GET    | /tasks/        | Get all tasks |
| POST   | /tasks/create/ | Create task   |

---

## 🧪 Testing

* Tested APIs using **Postman**
* Verified CRUD operations

---

## 🚀 Future Improvements

* Add user authentication system
* Build frontend using React
* Add task filtering and search
* Deploy on cloud platforms

---

## 👨‍💻 Author

Dibyajyoti Mishra

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
