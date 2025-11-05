# MyToDos_project
# My ToDos (Flask)
CRUD to-do app (Flask + SQLite/SQLAlchemy).

## Features
- Add/Edit/Delete/Mark done
- Filters (today/pending/completed)

## Quickstart
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
flask db upgrade      # if using migrations
flask run

## Env
cp .env.example .env
FLASK_ENV=development
SQLALCHEMY_DATABASE_URI=sqlite:///todo.db


## License
MIT


MyToDos_project/
├─ app.py                # or package/ with __init__.py
├─ models.py             # or app/models/
├─ templates/            # Jinja templates
├─ static/               # css/js
├─ requirements.txt
├─ .env.example
├─ README.md
├─ LICENSE
└─ migrations/           # if using Flask-Migrate

