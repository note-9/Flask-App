# 🔐 Flask Login App

A simple Flask web application with user authentication (login, logout, and registration) using SQLAlchemy for database interaction.

## 🧩 Description

This project demonstrates how to build a basic authentication system using Flask and SQLAlchemy. It supports:
- User registration
- User login/logout
- Password hashing
- Flash messaging for UX feedback

## 🚀 Features

- User registration & login with form validation
- Session-based authentication
- Password hashing with Werkzeug
- SQLite database using SQLAlchemy ORM
- Flash messages for login/register feedback

## 🛠️ Tech Stack

- **Language:** Python 3
- **Framework:** Flask
- **Database:** SQLite with SQLAlchemy ORM
- **Libraries:**
  - `Flask`
  - `Flask_SQLAlchemy`
  - `Werkzeug` (for password hashing)
  - `Jinja2` (for templates)

## 📦 Installation & Usage

### 🔧 Prerequisites
- Python 3.7+
- `pip` package manager

### 💻 Getting Started

```bash
# Clone the repository
git clone https://github.com/yourusername/flask-login-app.git
cd flask-login-app

# Create and activate virtual environment
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py
