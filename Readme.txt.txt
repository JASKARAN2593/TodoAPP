This application requires

## Functionality

- User registration and login
- Create, update, and delete tasks
- Set task priority, status, and reminder
- Display a list of user-specific tasks

## Install the required dependencies:

Set up the database

flask db init
flask db migrate -m "Initial migration"
flask db upgrade

Visit the local host to access the app

http://localhost:5000 to access the Todo App.

The application uses a SQLite database by default.