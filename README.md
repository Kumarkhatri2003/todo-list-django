# 📝 Django To-Do List Web App

A clean, responsive To-Do List web application built using **Django** and **Bootstrap 5**. The application allows users to effortlessly organize daily tasks, mark them as completed, and delete them upon completion.

---

## 📸 Preview

![To-Do List Application Preview](Screenshot%202025-08-03%20192735.png)

---

## 🚀 Key Features

- ➕ **Add New Tasks**: Quickly create tasks using Django Forms.
- ✅ **Mark as Complete**: Toggle task completion status with a single click.
- 🗑️ **Delete Tasks**: Remove tasks cleanly from the database.
- 🎨 **Responsive UI**: Polished and user-friendly interface built with Bootstrap 5.

---

## 🔧 Technologies Used

- **Backend**: [Python 3](https://www.python.org/) & [Django](https://www.djangoproject.com/)
- **Frontend**: HTML5 & [Bootstrap 5](https://getbootstrap.com/)
- **Database**: SQLite3
- **Version Control**: Git & GitHub

---

## 📁 Project Structure

```text
todo_project/
├── todo/                              # Core To-Do application
│   ├── migrations/                    # Database schema migrations
│   ├── templates/todo/
│   │   └── task_list.html             # Responsive task management UI
│   ├── forms.py                       # TaskForm definition
│   ├── models.py                      # Task model (title, completed)
│   ├── urls.py                        # App URL routing
│   └── views.py                       # Task views (list, complete, delete)
├── todo_project/                      # Project configuration
│   ├── settings.py                    # Django settings
│   ├── urls.py                        # Root URL routing
│   └── wsgi.py / asgi.py              # Server entry points
├── Screenshot 2025-08-03 192735.png  # Application screenshot
├── db.sqlite3                         # Local development database
├── manage.py                          # Django management CLI
└── README.md                          # Project documentation
```

---

## ▶️ Getting Started & Local Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Kumarkhatri2003/todo-list-django.git
cd todo-list-django
```

### 2. Create and Activate a Virtual Environment

- **On Windows (PowerShell):**
  ```powershell
  python -m venv venv
  .\venv\Scripts\Activate.ps1
  ```

- **On Windows (Command Prompt):**
  ```cmd
  python -m venv venv
  venv\Scripts\activate.bat
  ```

- **On macOS / Linux:**
  ```bash
  python3 -m venv venv
  source venv/bin/activate
  ```

### 3. Install Django

```bash
pip install django
```

*(Or if you have a `requirements.txt`: `pip install -r requirements.txt`)*

### 4. Apply Database Migrations

```bash
python manage.py migrate
```

### 5. Run the Development Server

```bash
python manage.py runserver
```

Open your browser and navigate to:
[http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## 🧭 Routes & Endpoints

| URL Pattern | View / Description |
| :--- | :--- |
| `/` | `task_list` - View all tasks and submit new tasks |
| `/complete/<id>` | `complete_task` - Mark a task as completed |
| `/delete/<id>` | `delete_task` - Remove a task permanently |

---

## 👤 Author

- **Kumar Khatri**
  - GitHub: [@Kumarkhatri2003](https://github.com/Kumarkhatri2003)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).