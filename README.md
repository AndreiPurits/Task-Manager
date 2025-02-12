# Task Manager

This is a simple Django-based Task Manager application that allows users to create, update, and manage tasks. It includes features like task prioritization, due dates, and user authentication. The project is built with Python, Django, and SQLite (can be replaced with other databases like PostgreSQL).

## Features

- User authentication (Login/Logout)
- Create, read, update, and delete tasks
- Task prioritization (Low, Medium, High)
- Due dates for tasks
- Responsive design using Bootstrap
- Simple and easy-to-use interface

## Requirements

- Python 3.x
- Django 3.x or higher
- SQLite (or another database if configured)

## Installation

Follow these steps to get the project up and running on your local machine.

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/taskmanager.git
cd taskmanager
```

### 2. Set up a Virtual Environment

It is recommended to use a virtual environment for Python projects.

```bash
python -m venv venv
source venv/bin/activate  # On Windows, use venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure the Database

Run the following command to set up the database and apply the migrations:

```bash
python manage.py migrate
```

### 5. Create a Superuser

To access the Django admin panel, create a superuser:

```bash
python manage.py createsuperuser
```

Follow the prompts to create the superuser.

### 6. Run the Development Server

Start the development server:

```bash
python manage.py runserver
```
Now you can access the application by navigating to http://127.0.0.1:8000/ in your browser.

# Usage

Task List: Displays all tasks. You can edit or delete existing tasks from this page.
Create Task: A form to create a new task. You can specify the title, priority, and due date.
Edit Task: If you want to update an existing task, you can modify the title, priority, and due date.

# Authentication

Users can log in to the application. Once logged in, they can create tasks, update them, and mark them as complete.

