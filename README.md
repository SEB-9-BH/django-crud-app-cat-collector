# Django Cat Collector Solution

## About

This repo contains the solution code for the Django CRUD App.

## Getting Started

1. Navigate into the project directory:

```sh
 cd django-crud-app-cat-collector
```

2. Install dependencies (this also creates the virtual environment if it doesn’t exist):

```sh
 pipenv install
```

3. Activate the virtual environment:

```sh
 pipenv shell
```

4. Set up your PostgreSQL database:

   - Ensure PostgreSQL is installed and running on your machine.
   - Create a database named `teas_db` if it does not already exist:

```bash
createdb catcollector
```

5. Open the application in Visual Studio Code:

```bash
code .
```

6. Make migrations:

```bash
python manage.py makemigrations
```

7. Migrate your changes:

```bash
python manage.py migrate
```

8. Run the server:

```bash
python manage.py runserver
```
