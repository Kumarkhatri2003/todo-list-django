📝 Django To-Do List App
A simple To-Do List web application built using the Django framework. You can add tasks, mark them as completed, and delete them.

🚀 Features
Add new tasks
Mark tasks as completed
Delete tasks
Responsive UI using Bootstrap 5
🔧 Technologies Used
Python 3
Django
Bootstrap 5
HTML5
📁 Project Structure
todo_project/
├── todo/
│   ├── templates/
│   │   └── todo/
│   │       └── task_list.html
│   ├── models.py
│   ├── views.py
│   └── urls.py
├── db.sqlite3
├── manage.py
└── README.md
▶️ How to Run Locally
Clone the repository:

git clone https://github.com/yourusername/todo-list-django.git
cd todo-list-django
(Optional) Create and activate a virtual environment:

python -m venv venv
# On Linux/macOS
source venv/bin/activate
# On Windows
venv\Scripts\activate
Install dependencies:

pip install -r requirements.txt
Run the Django development server:

python manage.py runserver
Open your browser and visit:

http://127.0.0.1:8000