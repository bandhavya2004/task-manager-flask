# Task Manager

A full-stack task management web app built with Flask, featuring user authentication and a SQLite database.

## Features
- User signup/login with hashed passwords (Flask-Bcrypt)
- Add, complete, and delete tasks
- Tasks are private per user
- Persistent storage with SQLite + SQLAlchemy
- Clean, responsive UI

## Tech Stack
- **Backend:** Python, Flask
- **Database:** SQLite, Flask-SQLAlchemy
- **Auth:** Flask-Login, Flask-Bcrypt
- **Frontend:** HTML, CSS

## Running Locally

\\\ash
git clone https://github.com/bandhavya2004/task-manager-flask.git
cd task-manager-flask
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python app.py
\\\

Then open http://127.0.0.1:5000 in your browser.

## Live Demo
[Add your deployed link here]
