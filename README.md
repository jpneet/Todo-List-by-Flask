# Flask Todo App

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Flask](https://img.shields.io/badge/Flask-2.3-green)
![SQLite](https://img.shields.io/badge/SQLite-3.39-orange)

A simple **Todo application** built with **Flask** and **SQLite**, allowing users to **create, update, and delete tasks** via a web interface.  

---

## 🚀 Features

- Add new tasks with **title** and **description**
- Update existing tasks
- Delete tasks
- Tasks stored in **SQLite database**
- Timestamp for task creation

---

## 🛠️ Tech Stack

- **Backend:** Python, Flask
- **Database:** SQLite (via SQLAlchemy)
- **Frontend:** HTML (Jinja2 templates)
- **Other:** datetime, os

---

## 💻 Installation

1. **Clone the repository:**
   ```bash
   git clone <repository_url>
   cd <repository_folder>
Create and activate a virtual environment (optional but recommended):
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

Install dependencies:
pip install Flask SQLAlchemy
Run the application:
python app.py
Open your browser and go to:
http://127.0.0.1:5000/

Flask-Todo-App/
│
├─ app.py              # Main Flask application
├─ todo.db             # SQLite database (auto-created)
├─ templates/
│   ├─ base.html       # Base template for shared layout
│   ├─ form.html       # Homepage template
│   └─ update.html     # Update task template
└─ README.md           # Project documentation


👤 Author

Japneet Singh
