DjangoEcommerce

## After cloning project:

### 1. Install packages & other dependencies ([install pipenv if you don't have it already](https://python-tutorials.in/install-pipenv-windows/))

```
pipenv install
```
### 2. Update the database
```
python manage.py makemigrations
python manage.py migrate
```

### 3. Run the server to test the application
```
python manage.py runserver
```
