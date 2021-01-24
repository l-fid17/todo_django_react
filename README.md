Django + React Todo App boilerplate

React app created with CRA + Django REST service.

Project bootstrapped with Pipenv and CRA.

To run the project on your machine please run the command below from within the root folder:
pipenv install
pipenv shell - to activate the venv and run djang commands
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
_in a new shell_
yarn
yarn start

Navigate to http://localhost:3000 to view the app
If you'd like CRA to open the React App automatically when starting the dev server remove the string BROWSER=none from the .env file in the frontend folder.

Django service running on port 8000
View the Django Admin panel at http://localhost:8000/admin (remember to create a superuser before attempting to log in)
The link to the api is /api/todos
